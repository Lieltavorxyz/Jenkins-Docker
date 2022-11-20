pipeline{
    agent {
        docker {image 'node:16.13.1-alpine'}
    }
    stages{
        stage("node"){
            steps{
                sh " node --version "
            }
        }
    }
}