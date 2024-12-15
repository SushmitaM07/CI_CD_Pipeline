pipeline {
  agent any
  stages{
    stage('Checkout') {
      steps {
        git url: 'https://github.com/SushmitaM07/CI_CD_Pipeline.git',branch:'main'
      }
    }
    stage('Build') {
      steps {
        echo 'Building the project...'
        //Add your build commands here
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deplying the project...'
        //Add your deployment commands here
      }
    }
  }
}
