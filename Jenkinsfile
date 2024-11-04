pipeline {
    agent { label 'linux-agent-k3s' }
    stages {
        stage('hello') {
            steps {
                sh 'echo Hello Jenkins!.... from github'
            }
        }
    }
}
