pipeline {
    agent { label 'test' }
    triggers {
        pollSCM('* * * * *')
    }
    stages {
        stage('hello') {
            steps {
                echo "Hello World!"
            }
        }
    }
}
