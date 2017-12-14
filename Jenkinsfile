pipeline {
    agent any

    stages {
        stage('Gradle build') {
            steps {
                bat "gradlew clean build"
            }
        }
    }
}