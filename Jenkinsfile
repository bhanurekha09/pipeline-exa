pipeline {
    agent any

    stages {
        stage( 'STAGE 1' ) {
            steps {
                echo 'excecuting script files'
                git 'https://github.com/bhanurekha09/pipeline-exa.git'
                
            }
        }
        
        
        stage( 'STAGE 2' ) {
            steps {
                echo 'excecuting first files'
                sh 'chmod +x one.sh'
                sh './one.sh'
                
            }
        }
    
    
     stage( 'STAGE 3' ) {
            steps {
                echo 'excecuting second files'
                sh 'chmod +x second.sh'
                sh './second.sh'
            }
        }
    
     stage( 'STAGE 4' ) {
            steps {
                echo 'excecuting third files'
                sh 'chmod +x third.sh'
                sh './third.sh'
                
            }
        }
    
     stage( 'STAGE 5' ) {
            steps {
                echo 'excecuting fourth files'
                  sh 'chmod +x fourth.sh'
                sh './fourth.sh'
                
            }
        }

     stage( 'STAGE 6' ) {
            steps {
                echo 'excecuting fifth files'
                  sh 'chmod +x fifth.sh'
                sh './fifth.sh'
                
            }
        }
    
    
    }
    
    }
