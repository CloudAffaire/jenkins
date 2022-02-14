pipeline {
    agent { label 'test' }
    triggers {
        pollSCM('H/20 * * * *')
    }
    stages {
        stage('hello') {
            steps {
                echo "Hello World!"
            }
        }
    }
}
