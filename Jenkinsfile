pipeline {
    agent any
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
