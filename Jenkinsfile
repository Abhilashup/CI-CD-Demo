pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                build 'calc.py'
            }
        }
      stages {
        stage('test') {
            steps {
                python 'test_calc.py'
            }
        }
    }
}
