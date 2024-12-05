pipeline {
    agent any
    stages {
        stage("Run Tests") {
            steps {
                bat './mvnw clean test'
            }
        }
    }
}