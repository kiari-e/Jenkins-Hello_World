pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                // Windows agent: use bat commands
                bat 'javac HelloWorld.java'
                bat 'java HelloWorld'
            }
        }
    }
}
