pipeline {
    agent any
    stages {
        stage('Pull from Git') {
            steps {
                git branch: 'develop', url: 'https://github.com/dmishra28/jenkins-practice-repo.git'
                echo "Code pulled successfully to workspace"
            }
        }
        stage('Show Workspace Content') {
            steps {
                echo "Listing workspace path and files for assignment screenshot:"
                sh 'pwd'
                sh 'ls -l'
            }
        }
    }
}

