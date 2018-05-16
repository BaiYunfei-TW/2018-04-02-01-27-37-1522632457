// Scripted //
node {
    agent any
	
	stage('Build') {
		buildInfo = rtGradle.run
	}
	stage('Test'){
		testInfo = rtGradle.test
	}
}