pipeline{
 agent any 
 environment {
      ver = "1.2.3"
        }
 stages { 
       stage('audit') { 
       steps {
             sh '''
                 git version
                 docker version
                 '''
              echo " build version ${ver} "
              }
          }
         }
       } 
        
