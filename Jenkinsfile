// Scripted //
node {
    checkout scm
	
	stage('Build') {
		buildInfo = rtGradle.run
	}
	stage('Test'){
		testInfo = rtGradle.test
	}
}