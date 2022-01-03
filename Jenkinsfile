pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                bat 'calc.py'
            }
        }
        stage('test') {
            steps {
                bat 'test_calc.py'
            }
        }
    }
}

