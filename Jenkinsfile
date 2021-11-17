pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello Worls!!"'
                sh '''
                    echo "Multiline shell works too"
                    ls -lah
                    pwd
                '''
            }
        }
    }
}
