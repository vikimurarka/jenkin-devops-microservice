pipeline {
	agent any
	stages{
		stage('Build') {
			steps{
			echo "Build"
			}
			
		}
		stage('Test') {
			steps {
			echo "Test"
			}
		}

		stage('Integeation-Test') {
			steps {
			echo "Test"
			}
		}
	} post {
		always {
			echo 'Post actions after all stage has run'
		}
		success {
			echo 'I run when build is suucessful'
		}
		failure {
			echo 'I run when build fails'
		}

	}
}
