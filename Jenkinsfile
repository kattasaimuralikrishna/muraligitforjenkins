pipeline{
    agent any
    stages{
        stage('SCM2'){
            steps{
               git 'https://github.com/GitPracticeRepo/java11-examples.git'
            }
        }
        stage('Build'){
            steps{
                sh 'mvn clean package'
            }
        }
        stage('shcommnd'){
            steps{
                sh '''
                sudo apt update
                echo "katta"

                '''
            }
        }
        stage('run'){
           steps{
                 sh '''
            chmod 777 ./run.sh
            ./run.sh
            
            '''
           }
        }
    }
}
