pipeline {
    agent any

    stages {
        stage('Descargar repo') {
            steps {
                git poll: true, url: 'https://github.com/carellomartino/repo-para-testear-jenkins.git'
                sh '''
                echo 'Repositorio descargado'
                '''
            }
        }
    }
                
}
