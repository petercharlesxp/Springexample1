pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''rm -rf springexample;
git clone https://github.com/petercharlesxp/springexample.git;
mvn clean -f springexample;'''
      }
    }
  }
}