pipeline {
    agent any
    tools{
        maven 'maven'
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                bat "C:\\Windows\\System32\\cmd.exe /c mvn clean test"
            }
        }
    }
}
