pipeline {
  agent any
  stages {
    stage('plan') {
      steps {
        echo 'I have a plan to work on CICD pipeline'
      }
    }

    stage('code') {
      steps {
        echo 'I have a code to work on CICD pipeline'
      }
    }

    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'I have a build to work on CICD pipeline'
          }
        }

        stage('test') {
          steps {
            echo 'I have a test to work on CICD pipeline'
          }
        }

        stage('release') {
          steps {
            echo 'I have a release to work on CICD pipeline'
          }
        }

        stage('deploy') {
          steps {
            echo 'I have a deploy to work on CICD pipeline'
          }
        }

        stage('operate') {
          steps {
            echo 'I have a operate to work on CICD pipeline'
          }
        }

      }
    }

  }
}