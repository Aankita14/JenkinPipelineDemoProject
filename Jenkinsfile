pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building the project...."
                bat "mvn clean"
            }
        }
        stage('Test') {
            steps {
                echo "Testing the project...."
                bat "mvn test"
            }
        }
        stage('compile') {
            steps {
                echo "complying the project...."
                bat "mvn compile"
            }
        }


        stage('Deploy') {
            steps {
                echo "deploying the project...."
                
            }
        }

    }
}
