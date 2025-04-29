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
    
    
        stage('node build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
                sh 'npm run test'
                
            }
        
        }
    }
}
