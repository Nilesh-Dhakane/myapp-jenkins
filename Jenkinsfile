Pipeline{
    agent any

    stages {
        
        stage('Build') {

            step {

                git branch: 'main', credentialsId: 'github', url: 'https://github.com/Nilesh-Dhakane/myapp-jenkins.git'
            }

        }
    }
}