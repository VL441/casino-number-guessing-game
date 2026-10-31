pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'rm -rf build'
                sh 'cmake  -DCMAKE_CXX_COMPILER=gcc -B build -S .' 
                sh 'cmake --build build'
            }
        }
    }
}


