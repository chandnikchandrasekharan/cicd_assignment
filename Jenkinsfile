pipeline {
    agent any
    tools {
        maven 'Maven'
    }

    stages {
        stage('Git Checkout') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/chandnikchandrasekharan/microservice_cicd.git']])
                echo 'Git Checkout Completed'
            }
        }


        
        

    }
}
