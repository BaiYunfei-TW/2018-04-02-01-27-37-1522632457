// Scripted //
node {
    checkout scm
	
	stage('Build') {
		echo 'Building...'
		sh './gradlew build'
	}
	stage('Test'){
		echo 'Testing...'
		sh './gradlew test'
	}
}