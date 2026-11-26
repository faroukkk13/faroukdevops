pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Compilation en cours..."'
      }
    }

    stage('Test') {
      steps {
        sh 'exit 1'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "Déploiement terminé"'
      }
    }

  }
}