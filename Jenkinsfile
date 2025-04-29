pipeline {
    agent any
    tools {nodejs "mynodejs"}
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git 'https://github.com/sunishgopinath/git2demo.git'
                sh 'cat file1.txt'
            }
        }
    }
    stages {
        stage('node build') {
            steps {
                echo 'install npm'
                sh 'npm install'
                
            }
        }
    }
}
