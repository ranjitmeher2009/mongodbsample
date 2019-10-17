@Library(jenkins-library@master)

pipeline {
    agent any
    stages {
        stage('Checkout'){
            steps {
                gitCheckout(
                    branch: 'master',
                    url: 'https://github.com/ranjitmeher2009/mongodbsam',
                    gitCredential: 'git_credentials'
                )
            }
        }

    }
}

