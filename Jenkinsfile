
pipeline {
  agent any
  stages { 
    stage('Setup') {
      steps {
        echo 'Configuracion del proyecto'
      }
    }
    stage('Unit Testing') {
        script {
          sh """
          python -m unittest discover -v -s test
          """
        }
      }
    }
    stage('Integration Testing') {
      steps {
        echo 'prueba'
    }
  }  
}
