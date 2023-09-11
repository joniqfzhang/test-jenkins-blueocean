pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'building'
          }
        }

        stage('ParalleBuild') {
          steps {
            echo 'parallebuilding'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'deploying'
      }
    }

  }
}