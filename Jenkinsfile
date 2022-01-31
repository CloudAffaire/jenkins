pipeline {
    agent { label 'test' }
    options {
        checkoutToSubdirectory('MyCustomDir')
    }
    stages {
        stage('checkout') {
            steps {
                sh 'pwd'
                sh 'ls -l'
            }
        }
    }
}
