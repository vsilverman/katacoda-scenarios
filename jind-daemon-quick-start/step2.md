# How-To Access the Jenkins Server

- In your own environment Jenkins server will be running at _localhost_.
- This training environment starts Jenkins server at the following url:
<https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com>

## Login to the Jenkins server

- Go to your **Jenkins host** tab
- The username is `admin`{{copy}}
- To find `<adminpassword>` do
`docker exec -it jen_qs cat /var/jenkins_home/secrets/initialAdminPassword`{{execute T1}}
Copy `<adminpassword>` and paste it into the unlock screen.

## Skip plugin installation

Use the "Select plugins to install" option in the Customize CloudBees Jenkins Distribution screen,  select None in the top panel of the window to unselect all plugins. Then click Install.
We do not need plugins for this quickstart

## Your Jenkins is ready
