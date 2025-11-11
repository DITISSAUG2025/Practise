pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                chmod +x hello.sh
                sh 'hello.sh'
            }
        }
    }
}
