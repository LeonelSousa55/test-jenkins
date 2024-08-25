pipeline {
    agent any

    stages {
        stage ('Build Docker Image'){
            steps {
                sh 'echo "Executando o comando Build Docker"'
            }
        }

        stage ('Push Docker Image'){
            steps {
                sh 'echo "Executando o comando Docker Push"'
            }
        }

        stage ('Deploy no Kubernates'){
            steps {
                sh 'echo "Executando o comando kubectl apply"'
            }
        }
    }
}
