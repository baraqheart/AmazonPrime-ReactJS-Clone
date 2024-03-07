pipeline {
    agent any
    stages {
        stage('SCM') {
            steps {
                git branch:'master', url:'https://github.com/baraqheart/AmazonPrime-ReactJS-Clone.git'
                
            }
        }
        
        stage('Build') {
            steps {
                //
                echo 'Build the app...........'
                sh 'npm install'
            }
        }
        stage('Test') {
             steps {
                        //
                echo 'TEst the code...............'
                sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                //
                echo 'packaging my file.........'
                sh 'npm start'
            }
        }
    }
}
