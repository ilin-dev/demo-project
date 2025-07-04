pipeline {
    agent { label 'Linux_build' }

    stages {
        stage('Timeout') {
            steps {
                retry(10) {
                    sh 'I am not going to work :c'
                }
            }
        }
    }
}
