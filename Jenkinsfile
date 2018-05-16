Jenkinsfile (Scripted Pipeline)
node {
	checkout scm
	
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