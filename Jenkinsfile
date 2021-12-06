pipeline {

    agent any

     stages {
        stage('checkout') {
            steps {

                git 'https://github.com/kuslapur/jenkins-multibranch.git'
            }
        }
        stage('Build') {
            steps {
                sh 'maven package'
            }
        }
      
    }
}

