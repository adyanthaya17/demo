pipeline {
    agent {label 'centosforeman'}
    stages {
        stage('Checking if IP has been assigned') {
            steps {
                sh ' ./home/jenkins/stage3.sh'
            }
        }
        stage('Check if machine is ready') {
            steps {
                sh '/home/jenkins/stage4.sh'
            }
        }
    }
}
