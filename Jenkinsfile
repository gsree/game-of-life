pipeline {
    agent any

    stages {
        stage('Source Code') {
            steps {
                git 'https://github.com/gsree/game-of-life.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'mvn clean install'
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
