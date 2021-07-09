pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Verify') {
            steps {
                echo 'Verify'
                input "please verify"
            }
        }
        stage('Bye') {
            steps {
                echo 'Bye World'
            }
        }
    }
}
