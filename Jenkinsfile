pipeline {
    agent any 
    stages {
        stage('Test') {
            steps {
                echo 'Apply image to test node'
                echo 'Specific test device'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Image to all node' 
                echo 'imageupdate'
            }
        }        
    }
}
