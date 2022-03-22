pipeline{
    agent any
    stages{
        stage('shcommnd'){
            steps{
                sh '''
                sudo apt update
                echo "katta"

                '''
            }
        }
        stage('scm'){
            steps{
                git url: 'https://github.com/kattasaimuralikrishna/muraligitforjenkins.git'
            }
            
        }
        stage('run'){
            sh '''
            chmod 777 ./run.sh
            ./run.sh
            
            '''
        }
    }
}
