pipeline {
  agent any
  stages {
    stage('email') {
      steps {
        emailext(subject: 'vladi test', body: 'this is my email \n yes it is', to: 'vladi.kaplun@gmail.com')
      }
    }
  }
}
