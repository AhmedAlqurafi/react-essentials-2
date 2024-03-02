pipeline {
    agent {
        node {
            label "docker-agent-python"
        }
    }
    triggers {
        pollSCM "*/5 * * * *"
    }
    stages {
        stage('Build') {
            steps {
                echo "Building..."
                sh  """
                echo "Doing building stuff..."
                """

            }
        } 
        stage('Test') {
            steps {
                echo "Testing..."
                sh  """
                echo "Doing testing stuff..."
                """
            }
        }
        stage('Deliver') {
            steps {
                echo "Testing..."
                sh  """
                echo "Doing testing stuff..."
                """
            }
        }
    }
}