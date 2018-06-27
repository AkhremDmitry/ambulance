pipeline {
    agent any


    stages {
        stage('Build') {
            steps {
                mvn install
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
    }
}