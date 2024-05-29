pipeline { 
    agent any 
            stages { 
                stage('Build') { 
                    steps { 
                        sh 'make build' // comando de construcción de tu proyecto 
                    } 
                } 
                stage('Test') { 
                    steps { 
                        sh 'make test' // comando para ejecutar pruebas 
                    } 
                } 
            } 
} 
