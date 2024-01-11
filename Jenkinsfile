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


    //             script {
    //                  configFileProvider(
    //     [configFile(fileId: 'maven-global-settings', variable: 'MAVEN_SETTINGS')]) {
    //     sh 'mvn -s $MAVEN_SETTINGS clean install'
    // }
    //             }
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
