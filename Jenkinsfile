pipeline{
      agent any //step-1
      stages{
        stage('Build'){
           steps{
            sh 'hostname -I'
           }
        }
        stage('Test'){
            steps{
                sh 'free -gh'
            }
        }
         stage('Deploy'){
            steps{
                sh 'df -kh'
            }
         }
      }


}
