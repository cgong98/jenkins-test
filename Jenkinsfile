pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
		echo "Build #1"
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing #1.."
                sh '''
                python3 helloworld.py
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}
