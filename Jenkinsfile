pipeline {
    agent { docker { image 'gcc' } }
    stages {
        stage('build') {
            steps {
                sh 'g++ -o main main.cpp'
            }
        }
    }
}
