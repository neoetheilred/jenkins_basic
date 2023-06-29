pipeline {
    agent: any

    stages {
        stage('Build') {
            steps {
                sh 'echo ok'
            }
        }
        stage('Test') {
            when {
                expression {
                    // build was successful
                }
            }
            steps {
                sh 'we did nothing'
            }
        }
    }
}