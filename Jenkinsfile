pipeline {
  agent {
    node {
      label 'node'
    }

  }
  stages {
    stage('init_env_variable') {
      steps {
        sh '''env.VARIABLE_1="10"
env.VARIABLE_2="7"'''
      }
    }
    stage('run main.js') {
      steps {
        sh 'sh \'node main.js\''
      }
    }
  }
  environment {
    var1 = 'VAR1'
  }
}