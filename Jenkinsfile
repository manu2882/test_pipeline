pipeline {
    agent any
        stages {
                stage ('one') {
                        steps {
                                echo "Hi, this is first pipeline from me"
                               }
                             }
                             
                stage ('two') {
                        steps {
                                input("Do you want to proceed?")
                                }
                               } 
                }
          }      
