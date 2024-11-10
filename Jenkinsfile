pipeline{
  agent any;
   stages{
    stage('Build'){
      steps{
       echo "this is build state"
        sh 'sleep 5'
      }
   }
     stage('deploy'){
      steps{
       echo "this is deploy state"
        sh 'sleep 5'
      }
   }
     stage('test'){
      steps{
       echo "this is test state"
      }
   }
}
}
