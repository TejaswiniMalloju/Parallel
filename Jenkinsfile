pipeline {
    agent any
    stages {
        stage('Parallel Stage') {
            parallel {
                stage('Stage 1') {
                    steps {
                        echo 'Running Stage 1'
                        // Add your commands for Stage 1
                    }
                }
                stage('Stage 2') {
                    steps {
                        echo 'Running Stage 2'
                        // Add your commands for Stage 2
                    }
                }
                stage('Stage 3') {
                    steps {
                        echo 'Running Stage 3'
                        // Add your commands for Stage 3
                    }
                }
            }
        }
    }
    post {
        success {
            echo 'Pipeline succeeded!'
            // Additional actions to perform if the pipeline succeeds
        }
        failure {
            echo 'Pipeline failed!'
            // Additional actions to perform if the pipeline fails
        }
    }
