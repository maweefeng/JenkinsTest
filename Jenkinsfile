pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'build starting'
                sh script: 'ls'
                sh script: 'pwd'
                echo env
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
