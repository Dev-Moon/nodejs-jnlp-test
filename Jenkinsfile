pipeline {
    agent {
        label 'nodejs-test'
    }

    stages {
        stage('Build') {
            steps {
                sh "node test.js"
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
