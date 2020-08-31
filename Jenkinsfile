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
	} 
	
	post {
		//five types of post action "always","success","failure","unstable","changed"
		always {
			echo 'Post actions after all stage has run'
		}
		success {
			echo 'I run when build is suucessful'
		}
		failure {
			echo 'I run when build fails'
		}
		unstable {
			echo 'when there is a test failue'
		}

		changed{
			echo 'I run only when status of build changes, either from success to fail or vice versa'
		}

	}
}
