pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '✅ Just a simple build stage running.'
                sh 'echo Hello from Linux'
            }
        }

        stage('Done') {
            steps {
                echo '🎉 Build Done!'
            }
        }
    }
}
