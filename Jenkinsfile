pipeline {

    agent any

    stages {
        stage('Make folders and files') {
            steps{
                bat '''
                mkdir testingPipeline
                echo "Some Things" > testingPipleine\file.txt
                '''
            }
        }
        stage('View') {
            steps {
                bat '''
                dir
                type testingPipeline\text.txt
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