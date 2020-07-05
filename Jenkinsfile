pipeline {
    agent any 
    stages {
        stage('checkout') {
            steps {

                git credentialsId: 'github', url: 'git@github.com:yessarath/devops.git'
                
            }
        }
        stage('deployment') {
            steps {

                sh 'cp *.html /var/www/html/'

            }
        }
        
    }
}
