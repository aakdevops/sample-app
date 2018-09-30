pipeline {
    agent {
        docker { image 'node:7-alpine'}
    }
    stage {
        stage('test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
