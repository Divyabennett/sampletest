pipeline { 
    agent any  
    stages { 
        stage('sample1') {
          steps {
            echo 'summition'
            bat 'mvn test'
          }
        }
        stage('sample 2') { 
            steps { 
               echo 'addition...' 
               bat 'mvn package'
            }
        }
   
}
    }
