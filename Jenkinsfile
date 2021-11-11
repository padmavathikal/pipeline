pipeline {
    agent any
    environment {
	//NEW_VERSION = '1.2.0'
	//SERVER_CREDEENTIALS= credentials('server-credentials')
        
        
    }
    stages {
        stage("init") {
            
        stage("build") {
            steps {
                echo " building the application.."
				echo " building the version "
            }
        }
        stage("test") {
            steps {
                script {
                    echo " testing the application "
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                 echo : "deploying the application "
                }
            }
        }
    }   
}
