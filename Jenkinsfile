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
				sh "/usr/bin/docker-compose down -v"
				sh "/usr/bin/docker-compose up --build -d"
			}
		}
	}
}