pipeline {
    agent{
        label "Linux"
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh '''
                    echo 'It is currently' date
                    pwd
                    uname -a
                    lscpu
                    '''
                node("Windows"){
                    bat '''
                        echo It is now %date% %time%
                        echo The current directory is %CD%
                        '''
                }
            }
        }
    }
}
