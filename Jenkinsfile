pipeline {
    agent any
    tools {
        gradle 'Gradle'    // Your Gradle installation name in Jenkins
        jdk 'JDK'           // Your JDK installation name in Jenkins
    }
    stages {
        stage('Build') {
            steps {
                sh 'gradle build'
            }
        }
    }
}

