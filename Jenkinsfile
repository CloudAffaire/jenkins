pipeline {
    agent { label 'test' }
    options {
	timestamps()
	overrideIndexTriggers(true)
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World!'
            }
        }
    }
}
