pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh '''
                    pwd
                    uname -a
                    sudo lshw -short
                    lscpu
                    '''
            }
        }
    }
}
