pipeline {
    agent none

    stages {
        stage("Build") {
            steps {
                echo '빌드..'
                git branch: 'main', credentialsId: 'gittest', url: 'https://github.com/inheelee/docker-next-app.git'
            }
        }
        stage("Test") {
            steps {
                echo "테스트.."
            }
        }
//         stage("Deploy")
    }
}