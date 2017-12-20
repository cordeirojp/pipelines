pipeline {
  agent any
  stages {
    stage('Stage 1.1') {
      parallel {
        stage('Stage 1.1') {
          steps {
            echo 'Step 1.1.1'
          }
        }
        stage('Stage 1.2') {
          steps {
            echo 'Step 1.2.1'
          }
        }
      }
    }
    stage('Stage 2') {
      steps {
        echo 'Step 2.1'
      }
    }
    stage('Stage 3.1') {
      parallel {
        stage('Stage 3.1') {
          steps {
            echo 'Step 3.1.1'
          }
        }
        stage('Stage 3.2') {
          steps {
            echo 'Step 3.2.1'
          }
        }
      }
    }
    stage('Stage 4') {
      steps {
        echo 'Step 4.1'
      }
    }
  }
}