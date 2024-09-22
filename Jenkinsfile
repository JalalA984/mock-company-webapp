pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                ./gradlew assemble
                 ./gradlew test
            }
        }
    }
}
