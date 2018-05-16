// Scripted //
node {
    checkout scm
	
	def rtGradle = Artifactory.newGradleBuild()
	
	stage('Build') {
		echo 'Building...'
		rtGradle.run
	}
	stage('Test'){
		echo 'Testing...'
		rtGradle.test
	}
}