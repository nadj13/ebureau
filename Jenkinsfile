pipeline {
    agent any 
    tools {
        maven 'M3'
    }
    stages {
        stage('Compile') { 
            steps {
                // 
                echo "Etape compile"
                bat 'mvn clean compile'
            }
        }
        stage('Test') { 
            steps {
                // 
                echo "etape test"
            }
        }
        stage('Package') { 
            steps {
                // 
                echo "etape package"
            }
        }
        stage('Deploy') { 
            steps {
                // 
                echo "étape deploy"
            }
        }
    }
}
