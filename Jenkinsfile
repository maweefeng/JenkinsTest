pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'build starting'

                script {
                    def test = 2 + 2 = 3 ? 'YES' : 'NO'
                    echo test
                }
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
