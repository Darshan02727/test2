pipeline {
  agent any;
  stages {
    stage ('Build') {
      steps{
        echo "This is build stage"
        sh 'sleep 5'

      }
    } 
        stage ('Test') {
          agent { label 'myslave' }
      steps{
        echo "This is Test stage"
        sh 'sleep 5'

      }
    }
    stage ('Deploy') {
      steps{
        echo "This is Deploy stage"
        sh 'sleep 5'

      }
    }
  }
}
