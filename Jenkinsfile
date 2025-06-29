pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
                    echo 'hi'
                    ls -al
                    # npm --version
                    # npm ci
                    cat /etc/*release*
                '''
            }
        }
        stage ('test') {
            steps {
                sh '''
                    echo 'test stage'
                    ls -al
                    cat /etc/*release*
                '''
            }
        } 
    }
}
