pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                python 'calc.py'
            }
        }
        stage('test') {
            steps {
                python 'test_calc.py'
            }
        }
    }
}

