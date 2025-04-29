pipeline {
    agent any
    
    
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
                sh 'npm install '
            }
        }
    }

}
