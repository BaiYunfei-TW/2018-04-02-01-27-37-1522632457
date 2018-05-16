// Declarative //
pipeline {
    agent anyS
	
    stages {
        stage('Build') {
            steps {
                sh './gradlew build'
            }
        }
        stage('Test'){
            steps {
                sh './gradlew test'
            }
        }
    }
}