pipeline {
    agent { docker { image 'python:3.9' }}

    stages {
        stage('1-Build') {
            steps {
                echo 'Start Build'
                echo 'Do something'
                echo 'End Build'
            }
        }
        stage('2-Test') {
        steps {
                echo 'Start Test'
                echo 'Do something'
                echo 'End Test'
            }
        }
        stage('3-Deploy') {
        steps {
                echo 'Start Deploy'
                echo 'Do something'
                echo 'End Deploy'
                sh 'python --version'
            }
        }
    }
}
