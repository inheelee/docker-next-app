pipeline {
    agent any

    stages {
        stage("Build") {
            git branch: 'main', credentialsId: 'gittest', url: 'https://github.com/inheelee/docker-next-app.git'
        }
        stage("Test") {
        }
//         stage("Deploy")
    }
}