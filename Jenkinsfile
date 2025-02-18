pipeline {
    agent {
        label 'windows' // Ensure this runs on a Windows agent
    }
    stages {
        stage('Print Message') {
            steps {
                bat 'echo Hello from Jenkins on Windows!'
            }
        }
    }
}
