pipeline {
    agent any
   
    stages {
        stage('start') {
            steps {
                sh "echo hello jenkins!!!"
            }
            post {
                failure {
                    sh "echo failed"
                }
                success {
                    sh "echo success"
                }
            }
        }
    }
}
