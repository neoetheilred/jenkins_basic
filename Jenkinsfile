pipeline {
    agent any
    tools {
        maven "M3"
        jdk "java17"
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn package'
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