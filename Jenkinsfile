pipeline {
    agent any

    stages {
        stage('---clean---') {
            steps {
                sh "mvn clean"
            }
        }
        stage('--test--'){
            steps {
                sh "mvn test"
            }
        }
        sstage('--package--') {
            steps {
                sh "mvn package"
            }
        }
    }
}
