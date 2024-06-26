# CI-CD in github actions

# CI
1. Based on action(push/pull) done on github, workflow runs

# CD - Deploy via docker 
1. Once code push on master branch in github, workflow runs
2. In workflow, login to docker hub then build thee code and push the image then,
3. Login to EC2 then pull latest docker image
