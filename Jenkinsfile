pipeline {
    agent any

    stages {
        stage('Welcome') {
            steps {
                echo '✅ Hello, Jenkins Pipeline!'
            }
        }

        stage('List Files') {
            steps {
                bat 'dir' // Windows라서 bat 사용
            }
        }
    }
}
