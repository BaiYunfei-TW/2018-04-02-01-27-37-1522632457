// Declarative //
pipeline {
    agent any
	checkout scm
	
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