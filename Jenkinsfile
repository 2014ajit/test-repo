pipeline {
    agent any
	environment { 
        JENKINS_WORKSPACE = "${env.WORKSPACE}"
    }

    stages {
        stage('Build') {
            steps {
				echo "Running on ${JENKINS_WORKSPACE}"
            }
        }

}

}