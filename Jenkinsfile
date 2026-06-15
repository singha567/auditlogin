pipeline { 
  agent any
  stages { 
    stage('Stage Build'){
      steps {
        echo "This is Build stage"
        sh "pwd"
        }
    }
     stage('Stage Test'){
      steps {
        echo "This is Test stage"
        sh "ls -lrt"
        }
    }
     stage('Stage Deploy') {
       steps {
         echo 'Deploying...'
         // Add deployment steps here
         }
      }
    }
    post {
        always {
            echo 'Pipeline finished!'
            // Add post-build actions here
        }
    }
  }
