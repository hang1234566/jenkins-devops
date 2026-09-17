pipeline {
    agent any

    stages {
        stage('Hello DevOps') {
            steps {
                sh 'echo "Hello DevOps!"'
            }
        }

        stage('Show Files') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Done') {
            steps {
                sh 'echo "Build Success!"'
            }
        }
    }
}