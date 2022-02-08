pipeline {
    node("Windows"){

        stages {
            stage('Hello') {
                steps {
                    echo 'Hello World'
                    bat '''
                        pwd
                        dir
                        '''
                }
            }
        }
    }

    node("Linux"){
        stages {
            stage('Hello') {
                steps {
                    echo 'Hello World'
                    sh '''
                        pwd
                        ls
                        '''
                }
            }
        }
    }
}
