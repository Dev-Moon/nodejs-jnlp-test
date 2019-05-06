pipeline {
    agent {
        label 'nodejs-test'
    }

    stages {
        stage('Build') {
            steps {
                sh "node test.py"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
