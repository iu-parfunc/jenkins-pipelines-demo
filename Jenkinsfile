pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Hello World!'
            }
        }
    }
    post { 
        always { 
            echo 'Bye World!'
        }
    }
}
