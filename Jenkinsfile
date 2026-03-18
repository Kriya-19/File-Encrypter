pipeline {
 agent { label 'agent1' }

 stages {
  stage('Build') {
   steps {
    sh 'echo "Running build on agent node"'
   }
  }

  stage('Test') {
   steps {
    sh 'echo "Running tests on agent node"'
   }
  }

  stage('Deploy') {
   steps {
    sh 'echo "Deploying from agent node"'
   }
  }
 }
}
