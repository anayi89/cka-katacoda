To update the version of the application to the latest version, use the `kubectl set image` command. The update needs to be deployed with the version number of the application.

To update Nginx application that was deployed in the previous step, run the following comand, `kubectl set image deployment/my-nginx nginx=nginx:1.16.1 --record`{{execute}}
