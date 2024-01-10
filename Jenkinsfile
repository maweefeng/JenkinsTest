pipeline {
    agent any
    environment {
        CC = 'clang'
    }

    tools {
        maven 'mvn-3.9.6'
    }
    stages {
        stage('build') {
            steps {
                echo 'build starting'
                sh script: 'ls'
                sh script: 'pwd'
                sh script: 'printenv'
                echo env.BUILD_NUMBER
                sh script: 'mvn clean test install'
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
