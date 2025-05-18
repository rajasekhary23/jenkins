pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello DevOps'
            }
        }
        stage('Linux meta') {
            steps {
                sh 'pwd'
                sh 'whoami'
                sh 'cat /etc/os-release'
            }
        }
    }
}

