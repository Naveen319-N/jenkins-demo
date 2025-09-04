pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Naveen319-N/jenkins-demo.git'
            }
        }
        stage('Build') {
            steps {
                bat 'echo Hello Naveen anna! Running Jenkins pipeline job'
                bat 'dir'
                bat '"C:\\Program Files\\Git\\bin\\bash.exe" hello.sh'
            }
        }
    }
}

