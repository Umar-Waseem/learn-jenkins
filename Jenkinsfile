pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello Build'
                // checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Umar-Waseem/Umar-Waseem.git']])
            }
        }
        stage('Test') {
            steps {
                echo 'Hello Test'
            }
        }
        stage('Push') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
