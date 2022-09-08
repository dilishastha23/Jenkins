pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('python') {
            steps {
                sh 'python3 test.py'
            }
        }
        stage('java1') {
            steps {
                sh 'javac test.java'
            }
        }
        stage('java2') {
            steps {
                sh 'java devops'
            }
        }
    }
}

