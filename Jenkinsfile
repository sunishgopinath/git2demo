pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git 'https://github.com/sunishgopinath/git1demo.git'
                sh 'cat file1.txt'
            }
        }
    }
}
