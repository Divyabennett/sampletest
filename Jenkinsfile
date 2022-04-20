pipeline { 
    agent any  
    stages { 
        stage('sample1') {
          steps {
            echo 'summition'
            bat 'python sample.py'
          }
        }
        stage('sample 2') { 
            steps { 
               echo 'addition...' 
              //bat 'mvn package'
            }
        }
   
}
    }
