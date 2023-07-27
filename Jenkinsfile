pipeline {
    agent { docker { image 'python:3.14-alpin'}}

    stages {
        stage('build'){
            steps{
                sh 'python --version'
            }
        }
    }

    post{
      always{
          echo 'Always, success or not'
      }
    }
}
  
