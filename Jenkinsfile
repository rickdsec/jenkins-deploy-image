pipeline {
    agent any 
    stages {
        stage('Check CSM') {
            steps {
                checkout scm
                echo 'Checkout SCM' 
            }
        }
    }
    stages {
        stage('Build image') {
            steps {
                echo 'Building image' 
            }
        }
    }

}

