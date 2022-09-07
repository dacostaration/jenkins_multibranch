pipeline {
  agent any
   stages {
    stage ('Build') {
      steps {
        sh 'echo "Hello User"'
        sh '''
          echo "Welcome to B2..."
          ls -lh
          '''
     }
   }
    stage ('test') {
      steps {
        sh 'echo "Hello Test for B2"'
        sh '''
          echo "This lists current dir"
          pwd
          ''' 
      }
    }
  }
}
