To edit a deployment, run the `kubectl edit deployment` command. This command retrieves the deployment, opens a text editor and applies the deployment with the updated version of it.

In the home directory is a YAML file that will deploy an Nginx application.

To view the YAML file, run the `ls`{{execute}} command.
To view the contents of the YAML file, run the `cat deployment.yml`{{execute}} command.
To deploy YAML file, run the `kubectl apply -f ~/deployment.yml`{{execute}} command.

To edit the Nginx application that has been deployed, run the `kubectl edit deployment/my-nginx`{{execute}} command.
