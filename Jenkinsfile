pipeline {

    agent any

     stages {
        stage('checkout GIT') {
            steps {

                git 'https://github.com/kuslapur/jenkins-multibranch.git'
            }
        }
        stage('Build') {
            steps {
                echo "hello world"
            }
        }
      
    }
}

