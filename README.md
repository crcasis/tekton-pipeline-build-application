# tekton-pipeline-build-application
An easy pipeline workflow that allows to deploy an application cloning some repositorires and building a Dockerfile 

# run application

create namespace - ` kubectl create ns ci`
install tasks - ` kubectl apply -f task.yaml`
install pipeline - ` kubectl apply -f pipeline.yaml`
create pipeline-run - ` kubectl create -f pipeline-run.yaml`