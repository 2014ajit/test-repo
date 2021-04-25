pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				echo "${BUILD_NUMBER}"
				echo " Starting ant build"
                sh "ant build.xml"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}