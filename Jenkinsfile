pipeline {
  agent any
  stages {
    stage('1-1Stage') {
      parallel {
        stage('1st Stage') {
          steps {
            echo 'Hello World'
            sleep 60
          }
        }

        stage('1-2 Stage') {
          steps {
            echo 'Bark'
          }
        }

      }
    }

    stage('2-1 Stage') {
      parallel {
        stage('2-1 Stage') {
          steps {
            echo 'Mellow'
          }
        }

        stage('2-2 Stage') {
          steps {
            echo 'Mow'
          }
        }

      }
    }

    stage('3-1 Stage') {
      steps {
        echo 'What\'s the Fox Say?'
      }
    }

  }
}