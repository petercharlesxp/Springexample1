pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd;
rm -rf springexample;
git clone https://github.com/petercharlesxp/springexample.git;
mvn clean -f springexample;'''
      }
    }
  }
}