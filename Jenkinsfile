pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
								sh "mvn clean pack -DskipTests"
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
