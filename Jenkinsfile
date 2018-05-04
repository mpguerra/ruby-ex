node {
    stage('buildImage'){
        openshiftBuild(buildConfig: 'ruby-ex', showBuildLogs: 'true')
    }
    stage('deployApplication'){
        openshiftDeploy(deploymentConfig: 'ruby-ex')
    }
}
