pipeline {
    agent any

    stages {
        stage('Step-1: Build the App ') {
            steps {
               sh 'mvn clean install -DskipTests' 
            }
        }
        stage('Step-2') {
            steps {
                echo "This is Step 2"
            }
        }
    }

}
