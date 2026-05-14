pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo '從 GitHub 拉程式'
            }
        }

        stage('Build') {
            steps {
                echo '開始建置'
                bat 'type app.txt'
            }
        }

        stage('Test') {
            steps {
                echo '執行測試'
                bat 'echo 測試成功'
            }
        }
    }
}