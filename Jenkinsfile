#!groovy
@Library('jenkins-shared-pipelines')

Map configMap = [
    application: "java",
    //skipStages: ["PCF Delete"]
]
if ( env.BRANCH_NAME.equalsIgnoreCase('master') ){
    pipelineDecision.applicationPipeline(configMap)
}
else{
    pipelineDecision.applicationPipeline(configMap)
} 