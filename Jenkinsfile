pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'g++ -o add_numbers add_numbers.cpp' // Compile the C++ program
            }
        }
        
        stage('Test') {
            steps {
                sh './add_numbers' // Run the compiled program
            }
        }
    }
}

