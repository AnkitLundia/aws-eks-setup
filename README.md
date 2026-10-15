Overall structure

1. Jenkins running locally for CI/CD 
2. AWS login credentials stored locally for all AWS operations
3. FGAC implementation using specific IAM roles
4. Terraform used to manage entire infra
5. Use a simple docker image for a CRUD app
6. Setup the entire networking to allow connections from outside VPC (if it is not charging anything)
7. Plan the setup and everything to calculate cost and see if it can be covered in free tier.
8. Only proceed if free tier can cover costs.
