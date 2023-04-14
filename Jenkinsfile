pipeline {
  agent any
  stages {
    stage('startesting') {
      steps {
        sh '''python3 -m pip -V
python3 -m pip freeze'''
      }
    }

    stage('think test') {
      parallel {
        stage('think test') {
          steps {
            sh '''ls -la
python3 -V'''
          }
        }

        stage('BRANCHING') {
          steps {
            echo 'deleting messages'
          }
        }

      }
    }

    stage('step end') {
      steps {
        sh '''ls -la
python3 -V'''
      }
    }

    stage('test file') {
      steps {
        sh '''ls -la
python3 -V'''
      }
    }

  }
}