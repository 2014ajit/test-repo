pipeline {
    agent any
    environment { 
        JENKINS_WORKSPACE = "${env.WORKSPACE}"
    }
    stages {
        stage('Example') {
            steps {
                echo "Running on ${JENKINS_WORKSPACE}"
            }
        }
    }
}