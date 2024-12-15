pipeline {
    agent any
    stages {
        stage("Build_stage") {
            steps {
                echo "Building Project...."
            }
        }
        stage("Test_stage") {
            steps {
                echo "Testing Project...."
            }
        }
        stage("Deploy_stage") {
            steps {
                echo "Deploying project...."
            }
        }
    }
    post {
        success {
            echo "Pipeline executed successfully!"
        }
        failure {
            echo "Pipeline failed. Please check the logs."
        }
        always {
            echo "Thank You"
        }
    }
}
