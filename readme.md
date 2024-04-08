In this project, we will be setting up a development environment on azure cloud using terraform as our IaC tool.

Requirements:
- An active azure account with a subscription.
- Code editor e.g VSCode.
- azure CLI and account configured on vscode.
- terraform installed on host.

Create a file called `main.tf`. This is how we will be provisioning infastructure through this file. Its going to contain all information and configuration of resources created in our azure cloud.

        touch main.tf

Next step is to add our providers into our main.tf
