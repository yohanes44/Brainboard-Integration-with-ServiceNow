# brainboard-integration

Brainboard Allows you to visually design and manage your cloud infrastructures using Terraform with best practices.

Deployment Stage

1, Install the update set, which is in the Global Scope.
   The update set in the Global Scope will allow the creation of Catalog Variables from other Scoped Apps.
2, Install the Scoped App from this Git repository.
   Brainboard Architecture Templates, Variables, Projects, and Environments are imported from the Brainboard API every 30 minutes.
   Therefore, you need to wait up to 30 minutes to see the Architecture Templates.
