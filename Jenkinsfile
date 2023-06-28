
pipeline {
    agent any
    
        environment {
        UPDATE_LOCATION = 'https://pavanpanchal1.github.io/live/'
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        
        stage('Add Files') {
            steps {
                script {
                    file('index.html')
                    echo "Added index.php to workspace"
                }
            }
        }
        
    }
    
}
