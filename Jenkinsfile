pipeline {
  agent any
  stages {
    stage('clone the code') {
      parallel {
        stage('clone the code') {
          steps {
            git(url: 'https://github.com/GopireddyVuyyuru/food.git', branch: 'master')
          }
        }

        stage('clone') {
          steps {
            git(url: 'https://github.com/GopireddyVuyyuru/ecomm.git', branch: 'master')
          }
        }

      }
    }

    stage('deploy') {
      steps {
        sleep 10
      }
    }

  }
}