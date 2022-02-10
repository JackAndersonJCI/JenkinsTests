pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh '''
                    pwd
                    uname -a
                    lscpu
                    '''
                node("Windows"){
                    bat '''
                        echo The current directory is %CD%
                        '''
                }
            }
        }
    }
}
