pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'build starting'
                sh script: 'ls'
                sh script: 'pwd'
                error 'this is error'
            }
        }

        stage('test') {
            steps {
                echo 'test starting'
            }
        }

        stage('deploy') {
            steps {
                echo 'deploy starting'
            }
        }
    }
}
