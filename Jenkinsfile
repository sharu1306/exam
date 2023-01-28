pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building progress is going on stop and start and start..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing is happening here goodwill...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying is happening.....'
            }
         
        }
       
    }
    post{
        always{
       emailext body: 'hello', subject: 'wish', to: 'sharat.g.13@gmail.com'
        }
    }
}
