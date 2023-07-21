## Workshop: Introduction to Terraform Cloud

### Terraform Cloud Workspaces

1. Deep dive into Workspaces in Terraform Cloud
2. Creating a workspace
3. Setting up workspace variables
4. Exercise: Create a workspace and set up variables

### Remote State Management

1. Understanding Terraform state
2. Benefits of remote state management in Terraform Cloud
3. State versioning and locking
4. Exercise: Migrate local state to Terraform Cloud

#### Collaborative Workflow and Access Control

1. Explanation of the remote workflow in Terraform Cloud
2. Setting up git integration
3. Team setup and access control in Terraform Cloud
4. Exercise: Collaborate on a shared workspace

#### Private Module Registry and Policy as Code

1. Publish private modules to the registry
2. Use private modules in a workspace

### Sentinel

1. Introduction to Policy as Code with Sentinel
2. Set a simple policy with Sentinel

#### Notifications and Reports

1. Notifications
2. Reports

### Environment Variables, Secrets

1. Environment variables
2. Secrets

### Terraform Cloud API

Certainly, here is the numbered list:

1. **Workspace Management:** Workspaces in Terraform represent an environment. The API lets you create, read, update, and delete workspaces. You can also list all workspaces and retrieve settings for a workspace.
2. **Run Management:** Terraform Cloud allows you to run `plan` and `apply` commands in a safe and predictable manner. The API allows you to create, read, list, and cancel runs. You can also apply, discard, or force-execute a run.
3. **Variable Management:** Variables in Terraform are parameters for your infrastructure code. The API lets you create, read, update, delete, and list workspace variables.
4. **State Versions:** Terraform maintains a state of your infrastructure. With the API, you can list, create, or show the state versions. You can also import state.
5. **Teams and Access Controls:** You can create, manage, and delete teams and team memberships. You can also manage access for a team in a workspace.
6. **Organizations:** The API allows you to manage organizations within Terraform Cloud. You can create, update, delete, and list organizations.
7. **API Tokens:** You can generate and manage tokens that allow you to authenticate with the API.
