# Concourse-Pipeline
This Techhub will help user to understand concourse with Gated type in pipeline
In order to create a "gated" step in a pipeline, a simple job that requires a manual trigger needs to be inserted into it.
the following fly command:
fly -t <your-concourse-alias> set-pipeline -p simple-gate -c gated-pipeline.yml
Concouse will automatically execute first Job ,Secand Job will be requiring manual trigger which is link between first and third Job
![gated](https://user-images.githubusercontent.com/76486190/192943485-be1afb66-951f-40e2-9b71-0088ccf3a599.png)
