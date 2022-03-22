pipeline{
    agent any
    stages{
        stage('git clone'){
            steps{
        git url: 'https://github.com/kattasaimuralikrishna/muraligitforjenkins.git'
            }
        }
        stage('shcommnd'){
            steps{
                sh '''
                sudo apt update
                echo "murali katta"

                '''
            }
        }
    }
}
