pipeline {
    agent any
    stages {
        stage("build") {
            tools {
                maven 'Maven'
            }
            steps {
                echo 'building the application...'
                sh "mvn install"
            }
        }
         stage("test") {
            steps {
                echo 'testing the application...'
            }
        }
         stage("deploy") {
            steps {
                echo 'deploying the application...'
            }
        }
    }
}
