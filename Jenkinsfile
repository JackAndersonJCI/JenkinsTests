/*pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                node("Linux"){
                    echo 'Hello World'
                    sh '''
                        pwd
                        ls
                        '''
                }

                node("Windows"){
                    echo 'Hello World'
                    bat '''
                        pwd
                        ls
                        '''
                }
            }
        }
    }
}*/
node("Linux"){
    echo 'Hello World'
    sh '''
        pwd
        ls
        '''
}