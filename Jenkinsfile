pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
    stage('groovycode_execution') {
            scripts{
                def name=jenkins
                println("Hello ${jenkins},welcome to groovy script")
                
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
