pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/prasaadt12/jenkins.git/'
            }
        }
        stage('Read_Contents') {
            steps {
                bat 'dir'
            }
        }
        stage('Read_file') {
            steps {
                print Readit.txt
            }  
        }
    }
    
}
