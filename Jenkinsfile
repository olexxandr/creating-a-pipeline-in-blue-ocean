pipeline {
  agent any
  stages {
    stage('init_env_variable') {
      echo "Initialization"
    }
    stage('run main.js') {
      steps {
        sh 'sh \'node main.js\''
      }
    }
  }
  environment {
    var1 = 'VAR1'
    VARIABLE_1="10"
    VARIABLE_2="7"
  }
}
