pipeline {

    agent any

    stages {
        stage('Make folders and files') {
            steps{
                bat '''
                echo "Step 1"
                '''
            }
        }
        stage('View') {
            steps {
                bat '''
                echo "Step 2"
                '''
            }
        }
        stage('Run') {
            steps {
                bat 'script.bat'
            }
        }
    }
}