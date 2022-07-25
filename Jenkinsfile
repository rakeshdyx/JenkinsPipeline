pipeline {
    agent {
        label 'docker-slave1'
    }

    stages {
        stage('TestScript') {
            steps {
                sh 'java -version'
                echo '....Get Working directory...'
                sh 'pwd'
            }
        }

    }
}