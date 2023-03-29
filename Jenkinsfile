#!groovy
@Library('jenkins-shared-pipelines@master')

Map configMap = [
    application: "node",
    //skipStages: ["PCF Delete"]
]
if ( env.BRANCH_NAME.equalsIgnoreCase('master') ){
    pipelineDecision.applicationPipeline(configMap)
}
else{
    pipelineDecision.applicationPipeline(configMap)
} 