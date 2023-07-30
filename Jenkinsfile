pipeline {
  agent any;
  stages {
    stage ('BUILD') {
      steps {
        echo "This is BUILD Stage"
        sh 'sleep 5'
      }
    }
    stage ('TEST') {
      steps {
        echo "This is TEST Stage"
        sh 'sleep 5'
      }
    }
    stage ('DEPLOY') {
      steps {
        echo "This is DEPLOY Stage"
        sh 'sleep 5'
      }
    }
    stage ('CHECK') {
      steps {
        echo "This is CHECK Stage"
        sh 'sleep 5'
      }
    }
     stage ('slave2') {
      steps {
        echo "To check"
        sh 'sleep 5'
        }
    }
  }  
}  
