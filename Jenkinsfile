pipeline{
    agent{
        label 'slave'
    }

    stages{
        stage('Print Host Name'){
            steps{
              sh 'hostname'
            }
        }
        stage('Ip Adress'){
            steps{
                sh 'hostname -I'
            }
        }
        stage('Details of CPU'){
            steps{
                sh 'lscpu'
            }
        }
        stage('Disk usage'){
            steps{
                sh 'df -kh'
            }
        }
        stage('Memmory usage'){
            steps{
                sh 'free -h'
            }
        }
        stage('Date'){
            steps{
                sh 'date'
            }
        }
    }
}
