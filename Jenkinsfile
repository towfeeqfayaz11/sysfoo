pipeline{

	agent any

	//global  tools configuration
	tools{
		maven 'Maven 3.6.3'
	}

	stages{

		stage('build'){
			steps{
				sh 'mvn compile'
			}
		}

		stage('test'){
			steps{
				sh 'mvn test'
			}

		}

		stage('package'){
			steps{
				sh 'mvn package'
			}

		}
	}
}