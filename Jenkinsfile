pipeline {
       agent any

 stages{
    stage('Server Details'){
        steps{
           echo "This will print my server details"
  } 
}
    stage('Details of server'){
       steps{
           sh 'uname -a'
   }
  }
  stage('Date Of server'){
       steps{
           sh 'date'
	   }
	 }
 stage('Disk usage'){
       steps{
           sh 'df -h'
    }
 }
stage('memory usage'){
       steps{
           sh 'free'
}}

stage('CPU Detailes'){
       steps{
           sh 'lscpu'

}}}}
