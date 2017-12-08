pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
               echo 'Hello'   
            }
        }
        stage('build1') {
            steps {
                build 'gitwebhook/priyansh'
            } 
        }
    }   
}
