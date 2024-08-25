pipeline {
    agent any

    stages {
         stage ('Build Docker Image'){
            steps {
                echo "Executando o comando Build Docker"
            }
        }

        stage ('Push Docker Image'){
            steps {
                echo "Executando o comando Docker Push"
            }
        }

        stage ('Deploy no Kubernates'){
            steps {
                echo "Executando o comando kubectl apply"
            }
        }
    }
}
