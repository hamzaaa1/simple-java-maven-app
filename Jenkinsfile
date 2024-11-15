pipeline {
    agent any  // This tells Jenkins to run the pipeline on any available agent.
    
    stages {
        stage('Build') { 
            steps {
                // This step runs Maven to clean, build, and package the Java application.
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
