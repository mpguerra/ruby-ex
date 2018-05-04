node {
    stage('buildImage'){
        openshiftBuild(buildConfig: 'pili-sample-app', showBuildLogs: 'true')
    }
    stage('deployApplication'){
        openshiftDeploy(deploymentConfig: 'pili-sample-app')
    }
}
