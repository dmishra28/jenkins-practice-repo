pipeline {
    agent any
    stages {
        stage('Pull from Git') {
            steps {
                git branch: 'develop', url: 'https://github.com/dmishra28/jenkins-practice-repo.git'
                echo "Code pulled successfully to workspace"
            }
        }
    }
}
