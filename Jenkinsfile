pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'Hellow'
        echo 'hello in stage1'
      }
    }
    stage('stage2') {
      steps {
        parallel(
          "stage2": {
            echo 'in Hellow stage2 '
            
          },
          "": {
            echo 'step1'
            
          }
        )
      }
    }
  }
}