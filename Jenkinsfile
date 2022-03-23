pipeline{
    agent any
    stages{
        stage('SCM'){
            steps{
               git 'https://github.com/GitPracticeRepo/java11-examples.git'
            }
        }
        stage('Build'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
