pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				echo "${BUILD_NUMBER}"
				echo " Starting ant build"
                sh "ant -f build.xml -Dbuild_parameter=${BUILD_NUMBER} -verbose"
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