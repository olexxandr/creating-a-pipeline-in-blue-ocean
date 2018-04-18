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
  }
  environment {
    var1 = 'VAR1'
  }
}