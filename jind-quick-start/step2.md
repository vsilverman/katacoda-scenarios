# How-To View Jenkins Dashboard

- In your own environment Jenkins server will be running at _localhost_.

- This training environment starts Jenkins server at the following url:
https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com

## Login to the Jenkins server

- Go to your [Jenkins host](https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com). You should see the Jenkins web interface with the Installation wizard.

- To unlock the Jenkins instance - go to the terminal and find the following message in the startup log:

            *************************************************************

            Jenkins initial setup is required. An admin user has been created
            and a password generated.
            Please use the following password to proceed to installation:

            <PASSWORD>

            This may also be found at: /var/jenkins_home/secrets/initialAdminPassword

            *************************************************************

- Copy the password and paste it into the unlock screen.

## Skip plugin installation

Use the "Select plugins to install" option in the Customize CloudBees Jenkins Distribution screen,  select None in the top panel of the window to unselect all plugins. Then click Install.
We do not need plugins for this quickstart

## Your Jenkins is ready
