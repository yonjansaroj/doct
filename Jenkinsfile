pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "This is build stage"
                sh 'sleep 3'
                sh 'exit 1'
            }
        }
        stage('Test') {
            steps {
                echo "This is test stage"
                sh 'sleep 3'
            }
        }
        stage('Deploy') {
            steps {
                echo "This is deploy stage"
                sh 'sleep 3'
            }
        }
    }
}
