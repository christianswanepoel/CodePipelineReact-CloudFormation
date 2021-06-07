# CloudFormation Examples

# Query Pipeline

aws codepipeline --region eu-west-2 list-pipelines
aws codepipeline --region eu-west-2 get-pipeline --name CodePipelineReact-CodePipeline-NHETY43R50D5
aws codepipeline --region eu-west-2 list-pipeline-executions --name CodePipelineReact-CodePipeline-NHETY43R50D5
aws codepipeline --region eu-west-2 list-pipeline-executions --pipeline-name CodePipelineReact-CodePipeline-NHETY43R50D5
aws codepipeline --region eu-west-2 list-pipeline-executions --pipeline-name CodePipelineReact-CodePipeline-NHETY43R50D5 |grep status
aws codepipeline --region eu-west-2 list-pipeline-executions --pipeline-name CodePipelineReact-CodePipeline-NHETY43R50D5 |grep status |head
