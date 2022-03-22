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
