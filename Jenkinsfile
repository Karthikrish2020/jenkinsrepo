pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "Job started by Karthikeyan"
                echo "I am in Dev Job"
            }
        }
        stage('Build') {
            steps {
                echo "BUILDING"
            }
        }
        stage('Deploy'){
            steps {
                echo "Deploying"
            }
        }
        stage('Test') {
            steps {
                echo "Testing"
            }
            
        }
        stage('Release') {
            steps {
                echo "Releasing"
                echo "Released"
                
            }
        }
    }
}
