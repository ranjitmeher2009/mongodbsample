node {
    stage('Checkout'){
           checkout([
            $class: 'GitSCM', 
            branches: [[name: '*/master'],[name: '*/develop']], 
            doGenerateSubmoduleConfigurations: false, 
            extensions: [], submoduleCfg: [], 
            userRemoteConfigs: [[credentialsId: 'git_credentials', url: 'https://github.com/ranjitmeher2009/mongodbsample']]
            ])
    }
}

