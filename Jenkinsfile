pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'building build'
            }
        }
        stage('Test') {
            steps {
                echo 'Test build'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deply build'
            }
        }
        
    }
    post{
        always{
            emailext body: 'enjoy life ', subject: 'pipeline status ', to: 'nallapothulav.kalya@hcltech.com'
        }
    }
}
