pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Using Maven to compile the code.'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit tests with JUnit and integration tests with Selenium.'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analysing code quality using Checkstyle.'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Scanning for vulnerabilities using OWASP Dependency Check.'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to AWS EC2 staging instance.'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging environment.'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying to AWS EC2 production instance.'
            }
        }
    }
}
