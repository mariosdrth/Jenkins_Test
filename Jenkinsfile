pipeline {
    agent any
    options {
        quietPeriod(5)
    }
    stages {
        stage ('First Stage') {
            steps {
                sh 'echo First Stage...'
            }
        }
        stage ('Second Stage') {
            steps {
                sh 'echo Second Stage...'
            }
        }
        stage ('Third Stage') {
            steps {
                sh 'echo Third Stage...'
            }
        }
    }
}