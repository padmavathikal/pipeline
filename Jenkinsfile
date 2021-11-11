pipeline {
    agent any
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
