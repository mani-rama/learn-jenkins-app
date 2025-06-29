pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
                    echo 'hi'
                    ls -al
                    # npm --version
                    npm ci
                    cat /etc/*release*
                '''
            }
        }
    }
}
