pipeline {
    agent any
    
    stages {
        stage('Hello') {
            node("Linux"){
                steps {
                    echo 'Hello World'
                    sh '''
                        pwd
                        ls
                        '''
                }
            }

            node("Windows"){
                steps {
                    echo 'Hello World'
                    bat '''
                        pwd
                        ls
                        '''
                }
            }
        }
    }
}
