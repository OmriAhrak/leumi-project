GENERAL GUIDELINES : 
we have jenkins server and agent server with a credential for aws , also in jenkins we use docker plugin.
genrated an ssh key for the agent.
iam roles for the needed access.
an aws cli installed in the agent.
pulled the source code and dependencies from github , build an image using jenkins + docker plugin , after that i pushed the image created to ecr.
deploy the image using eks. 
