pipeline {
    agent any // Use any available agent (node) for running the pipeline

    stages {
        stage('Create Directory') {
            steps {
                // Use the 'bat' step to execute a Windows command
                bat 'mkdir C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\ff'
            }
        }
    }
}
