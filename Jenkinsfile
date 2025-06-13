pipeline {
    agent any
       stages {
          stage('Checkout') {
             steps {
                git branch: 'main', url: 'https://github.com/irphan7982/jenkins-test.git'
                }
             }

           stage('Build') {
             steps {
                sh './hello.sh'
                }
             }
           stage ('Test') {
             steps {
                echo 'Testing'
                }
             }
           stage ('Deploy') {
             steps {
                echo 'Deploying'
                }
             }
        }
}

