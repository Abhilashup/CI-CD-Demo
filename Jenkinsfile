pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                build calc.py
            }
        }
      stages {
        stage('test') {
            steps {
                test test_calc.py
            }
        }
    }
}
}
