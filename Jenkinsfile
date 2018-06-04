pipeline {
    agent any 
    stages {
        stage('Test') {
            steps {
                echo 'Apply image to test node'
                sh "/usr/bin/ssh 172.17.0.1 /usr/bin/python /home/jenkins/push-image.py node001"
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
