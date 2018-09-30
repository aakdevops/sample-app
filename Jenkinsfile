pipeline {
    agent {
	docker 'openjdk:8-jre'
    }
    stages {
        stage('test') {
            steps {
                echo "${env.BRANCH_NAME}"
		sh 'java -version'
            }
        }
    }
}
