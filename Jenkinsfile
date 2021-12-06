pipeline {

    agent any

     stages {
        stage('checkout Branch  GIT') {
            steps {

                git 'https://github.com/kuslapur/jenkins-multibranch.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Hello world'
            }
        }
      
    }
}

