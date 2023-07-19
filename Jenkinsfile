pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        checkout(
          $class: 'GitSCM',
          branches: [[name: '23Q1'], [name: '23Q2'],  [name: '23Q3']],
          doCheckout: 'true'
        )
      }
    }
  }
}
