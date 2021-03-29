pipeline {
    agent docker { image 'espressif/idf:latest' }
    stages {
        stage('build') {
            steps {
                echo 'build'
            }
        }
        stage('test') {
            steps {
                echo 'test'
            }
        }
        stage('deliver') {
            steps {
                echo 'deliver'
            }
        }
    }
}
