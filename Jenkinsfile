pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				echo "${BUILD_NUMBER}"
				echo " Starting ant build"
                sh "ant build.xml -verbose"
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