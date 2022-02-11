pipeline {
    agent{
        label "Linux"
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh '''
                    currentDate=`date`
                    echo It is currently $currentDate
                    pwd
                    uname -a
                    lscpu
                    '''
                /*node("Windows"){
                    bat '''
                        echo It is now %date% %time%
                        echo The current directory is %CD%
                        '''
                }*/
            }
        }
    }
}
