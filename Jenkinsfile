pipeline {
    agent {
        dockerfile true
    }
    stages {
        stage('test') {
            steps {
                sh 'echo "${env.BRANCH_NAME}"'
            }
        }
    }
}
