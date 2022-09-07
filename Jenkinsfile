pipeline {
    agent any 
    stages{
        stage('buks'){
            steps{
                sh 'whoami'
                sh 'lsblk'
            }
        }
        stage('tola'){
            steps{
                sh 'ls'
                sh 'lscpu'
                sh 'chmod +x wale.sh'
                sh 'bash -x wale.sh'
            }
        }
    }
}