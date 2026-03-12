pipeline {
    agent any
    stages {
            stage('Stage 1') {
            steps {
                echo 'Hello world!'
                sh 'rm -rf build'
            }
        }
        stage('Build') { 
            steps {
                sh 'rm -rf build'
                /*sh 'cmake -B build -S .' 
                sh 'cmake --build build' */
            }
        }
    }
}
