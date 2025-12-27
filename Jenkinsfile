pipeline{
    agent any

    stages {

        stage('Build') {

            steps {

                git branch: 'main', credentialsId: 'github', url: 'https://github.com/Nilesh-Dhakane/myapp-jenkins.git'
            }

        }

         stage('Build') {

            steps {

                sh 'docker build -t myapp:latest'
            }

        }
    }
}