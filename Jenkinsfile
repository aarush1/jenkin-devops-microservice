pipeline {
//agent any

agent { docker {image 'maven:3.6.3'}}

stages{
	stage('Build'){
		steps{
			echo "Build"
		}
	}

	stage('Test'){
		steps{
			echo "Test"
		}
	}

	stage('Integration Test'){
		steps{
			echo "Integration Test"
		}
	}

}

post{
	always{
		echo 'Im Awesome I run always'
	}

	success{
		echo 'I run when you are sucessful'
	}

	failure{
		echo 'I run when failure'
	}

}





}

	
