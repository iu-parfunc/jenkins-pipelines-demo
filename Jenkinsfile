pipeline {
    agent any
    triggers {
        pollSCM('')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Hello World!'
                exit 1
            }
        }
    }
    post { 
        always { 
            echo 'Bye World!'
        }
    }
}
