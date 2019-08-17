pipeline{
    agent any
    
    stages {
        stage ('Json check') {
            steps {
                sh 'cat list.json | json'
            }
        }
    }
}
