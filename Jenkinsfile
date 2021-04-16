pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'docker run --rm -v $PWD:/project -w /project espressif/idf idf.py build'
      }
    }

  }
}