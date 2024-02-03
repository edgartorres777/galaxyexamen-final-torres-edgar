pipeline{
	agent any
	stages{
		stage ('Build'){
			steps{
				echo "Etapa en no disponible"
			}
		}
		stage ('Tests'){
			steps{
				echo "Etapa test no disponible"
			}
		}
		stage ('Deploy'){
			steps{
				sh "docker-compose down -v"
				sh "docker-compose up -d --build"
			}
		}
	}
}