pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            if (fileExists('code.py')) {
                echo 'Yes'
            } else {
                echo 'No'
            }
        }
    }
}