pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
			echo 'Git checkout..'            
			}
        }
        stage('build') {
            steps {
                sh 'java Main.java'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
