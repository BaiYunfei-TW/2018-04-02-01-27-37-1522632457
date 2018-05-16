Jenkinsfile (Declarative Pipeline)
pipeline {

    stages {
        stage('Build') {
            steps {
                sh './gradlew build' 
            }
        }
		stage('Test') {
            steps {
                sh './gradlew make' 
            }
        }
    }
}