pipeline {
    agent any 
    stages {
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		sh 'sudo cp index.cgi /usr/lib/cgi-bin/'
		sh 'chmod 755 /usr/lib/cgi-bin/index.cgi'
            }
        }    



    }
}
