# Jenkins
Create jenkins image as in jenkins directory.

# Remote host
Create remote centos machine in a docker container ir orden to execute a job from Jenkins.
In order to connect to this remote host, run ssh command inside jenkins container:

`docker exec -it jenkins bash`

`ssh remote_user@remote_host`

or, with remote-key generated before, use:

`ssh -i <remote-key-path> remote_user@remote_host`
