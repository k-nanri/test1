pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                mvn clean
                mvn install
                mvn compile
                mvn package
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}