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
                echo 'Building'
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

