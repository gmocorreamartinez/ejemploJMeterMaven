pipeline {
    agent any

    stages {
        stage('Load') {
            steps {
                //sh "mvn verify -Pperformance"
                bat "mvn verify -Pperformance"
            }
        }
    }
}
