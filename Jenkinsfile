pipeline{
  agent any
  stages{
    stage('Checkout'){
      steps{
        retry(3){
          echo "pull github codes"
          error "Error in Retry"
        }
        echo "after retry(3)"
      }
    }
  }
}
