pipeline {
    agent any
    tools {
        maven "M3"
        jdk "jdk17"
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
                echo 'supposed to build'
            }
        }
        stage('Test') {
            steps {
                sh 'echo we did nothing'
            }
        }
    }
}