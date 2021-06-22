pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is ncpani'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
                   }
            stage('Deploy Productionncp') {
                  steps {
                        echo "Deploying in Production Areancp"
                  }
            }
      }
}
