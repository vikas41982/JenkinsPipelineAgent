  
pipeline {
   agent {
       label 'slavejenkins'
   }

   stages {
      stage('Hello') {
         steps {
                echo "Get Java Version"
                sh 'java -version'
                echo "Get working directory"
                sh 'pwd'
         }
      }
   }
}
