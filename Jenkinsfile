pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                build calc.py
            }
        }
        stage('test') {
            steps {
                python test_calc.py
            }
        }
    }
}

