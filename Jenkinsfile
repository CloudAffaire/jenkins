pipeline {
    agent { label 'test' }
    triggers {
        pollSCM('5 * * * *')
    }
    stages {
        stage('hello') {
            steps {
                echo "Hello World!"
            }
        }
    }
}
