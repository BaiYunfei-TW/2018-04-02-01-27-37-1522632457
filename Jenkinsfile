// Declarative //
pipeline {
    agent any
	
    stages {
        stage('Build') {
            steps {
                buildInfo = rtGradle.run
            }
        }
        stage('Test'){
            steps {
                testInfo = rtGradle.test
            }
        }
    }
}