pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Simple pipeline configured with Jenkinsfile."
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
