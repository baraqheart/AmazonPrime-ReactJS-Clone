pipeline {
    agent any
    stages {
        stage('SCM') {
            steps {
                git branch:'master', url:'https://github.com/baraqheart/AmazonPrime-ReactJS-Clone.git'
                //
            }
        }
        stage('Package') {
            steps {
                //
                echo 'packaging my file.........'
            }
        }
        stage('Build') {
            steps {
                //
                echo 'Build the app...........'
            }
        }
        stage('Test') {
             steps {
                        //
                echo 'TEst the code...............'
            }
        }

    }
}
