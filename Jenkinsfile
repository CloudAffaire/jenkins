pipeline {
    agent { label 'test' }
    options {
	timestamps()
	overrideIndexTriggers(false)
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World!'
        	echo env.BRANCH_NAME
            }
        }
    }
}
