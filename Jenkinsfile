pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Clone your repository
                git 'https://github.com/your/repository.git'
            }
        }

        stage('Test') {
            steps {
                // Install Python dependencies
                sh 'pip install -r requirements.txt'

                // Run the Python script to add two numbers
                sh 'python add_numbers.py'
            }
        }
    }
}
