node {
    stage('buildImage'){
        openshiftBuild(buildConfig: 'pili-sample-app-pipeline', showBuildLogs: 'true')
    }
    stage('deployApplication'){
        openshiftDeploy(deploymentConfig: 'pili-sample-app')
    }
}
