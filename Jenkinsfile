pipeline {
    agent any
    environment {
        CC = 'clang'
    }
    stages {
        stage('build') {
            steps {
                echo 'build starting'
                sh script: 'ls'
                sh script: 'pwd'
                sh script: 'printenv'
                echo env.BUILD_NUMBER
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
