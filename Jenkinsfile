pipeline {
    agent {
	label 'windows'
    }
    stages {
        stage('checkout') {
            steps {
                checkout scm
                bat 'dir /od'
            }
        }
    }
}
