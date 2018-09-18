pipeline {
    agent {label 'centosforeman'}
    stages {
        stage('Checking if IP has been assigned') {
            steps {
                sh 'test.sh '
            }
        }
      }
    }
}
