pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Paulo and this is the init'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building the build stage of the Pipeline'
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
      }
}