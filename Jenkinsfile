pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Hello Git'
      }
    }

    stage('Hello Girish') {
      steps {
        
        input(message: 'Deploy to QA?', ok: 'Yes')
        echo 'Hello World'
      }
    }

  }
}
