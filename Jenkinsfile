pipeline{
	agent any
	stages{
		stage ('Build'){
			agent {
                    docker { image 'maven:3.6.3-openjdk-11-slim' }
					echo "Etapa concluida"
            }
		}
		stage ('Tests'){
			steps{
				echo "Etapa test no disponible"
			}
		}
	}
}