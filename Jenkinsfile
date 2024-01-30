pipeline {
    agent any

    stages {
        stage("GIT CHECKOUT") {
            steps{
                git branch: 'main', url: 'https://github.com/annumehla/java-app.git'
            }
        stage("UNIT TEST") {
            steps{
                sh 'mvn test'
            }
        }
    }
}
