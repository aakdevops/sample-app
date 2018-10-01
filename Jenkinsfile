pipeline {
    agent {
        docker 'node'
    }
    stages {
        stage('test') {
            steps {
                echo 'hello! this is alpha branch build test going on. You will see node version next.'
                sh 'node --version'
            }
        }
    }
}
