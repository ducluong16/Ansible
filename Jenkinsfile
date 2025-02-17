pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                // Clone repository từ GitHub (đảm bảo branch chính là 'main' hoặc thay đổi theo repo của bạn)
                git url: 'https://github.com/ducluong16/Ansible.git'
            }
        }
    }
}
