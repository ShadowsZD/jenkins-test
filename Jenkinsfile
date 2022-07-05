pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            when {fileExists('code.py')}
            steps {
                echo 'Code exists, execute'
            }
        }
    }
}