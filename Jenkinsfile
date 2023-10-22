pipeline {
    agent {dockerfile true}
    stages {
        stage ('test') {
          steps { 
            sh """
               docker compose up
            """
            }
        }
    }
}