pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Stage 1: Build - Building the code using Maven"
                echo "Tool: Maven - A build automation tool for compiling and packaging code"
                echo "mvn clean package"
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo "Stage 2: Unit and Integration Tests"
                echo "Running unit tests to ensure code functions as expected"
                echo "Tool: JUnit - A unit testing framework for Java applications"
                echo "Running integration tests to ensure components work together"
                echo "Tool: Selenium - An integration testing tool for web applications"
            }
        }

        stage('Code Analysis') {
            steps {
                echo "Stage 3: Code Analysis"
                echo "Analysing the code to ensure it meets industry standards"
                echo "Tool: SonarQube - A code quality and security analysis tool"
            }
        }

        stage('Security Scan') {
            steps {
                echo "Stage 4: Security Scan"
                echo "Performing a security scan to identify vulnerabilities"
                echo "Tool: OWASP Dependency-Check - Scans dependencies for known vulnerabilities"
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo "Stage 5: Deploy to Staging"
                echo "Deploying the application to the staging server"
                echo "Tool: AWS CLI - Deploying to AWS EC2 staging instance"
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo "Stage 6: Integration Tests on Staging"
                echo "Running integration tests on the staging environment"
                echo "Tool: Postman/Newman - API testing on the staging environment"
            }
        }

        stage('Deploy to Production') {
            steps {
                echo "Stage 7: Deploy to Production"
                echo "Deploying the application to the production server"
                echo "Tool: AWS CLI - Deploying to AWS EC2 production instance"
            }
        }
    }
}
