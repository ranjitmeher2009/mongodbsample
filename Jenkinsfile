@Library('jenkins-library@master') _

pipeline {
    agent any
    stages {
        stage('Checkout'){
            steps {
                gitCheckout(
                    branch: 'master',
                    url: 'https://github.com/ranjitmeher2009/mongodbsample',
                    gitCredential: 'git_credentials'
                )
            }
        }

    }
}

