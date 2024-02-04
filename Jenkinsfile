pipeline{
	agent any
	stages{
		stage ('Build'){
			agent {
                docker { image 'maven:3.6.3-openjdk-11-slim' }
            }
			steps {
				sh 'mvn -B verify'
				archiveArtifacts artifacts: 'target/*.jar', fingerprint: true, onlyIfSuccessful: true
			}
		}
		stage ('Tests'){
			steps{
				echo "Etapa test no disponible"
			}
		}
	}
}