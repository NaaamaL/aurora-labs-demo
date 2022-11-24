pipeline {
    agent any

    stages {
        stage('Clone github repo') {
            steps {
                script {
		    git branch: 'main', credentialsId: 'da6ce258-46aa-485c-aefe-67caac0e6783', url: 'https://github.com/NaaamaL/aurora-labs-demo/'
		    sh "ls aurora-labs-demo"
		}
            }
        }
    }
}
