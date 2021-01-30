pipeline {
    agent any
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "Initialization starts"
                ''' 
            }
        }

        stage ('Build') {
            steps {
                echo 'This is a minimal pipeline.'
            }
        }
        stage ('SonarQube Scan') {
            steps {
                echo 'Sonar Scan Done'
            }
        }
        stage ('Deploy') {
            steps {
                echo 'Deployement started...'
            }
        }
    }
}
