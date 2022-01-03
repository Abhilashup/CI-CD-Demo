pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                build 'calc.py'
            }
        }
        stage('test') {
            steps {
                test 'test_calc.py'
            }
        }
    }
}

