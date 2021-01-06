# Module 2 Lab

Created: Jan 5, 2021 10:43 AM
Tags: AZ-104

# Assign RBAC Permissions

- Make sure you're using the correct directory

    If you haven't changed anything singe the Module 1 Lab, you might still be in the new, test tenant. 

- Create a new test user
    - Elevate yourself with Privileged Identity Management to Global Admin
    - Create a new test user in the directory
- Assign permissions of your Resource Group
    - Find your dedicated Resource Group and navigate to the management pane
    - Access control (IAM)
    - Explore who has permissions
    - Grant your test user "Storage Account Contributor" permissions on your Resource Group
- Test those permissions
    - Start a new Private/Incognito browser window
    - Log in with your test user
    - Find your dedicated Resource Group
    - Create a new Storage Account, settings will be mostly irrelevant
    - Try creating something else, for example, Key Vault, Virtual Network

# Deploy an Azure Policy

- Make sure you're using the correct context

    Check if you're using the correct identity and correct directory.

- Assign a Policy
    - Navigate to the Policy pane from the portal menu, go to Definitions
    - Explore both the built-in and custom policy definitions
    - Find the definition "Add a tag to resources"
    - Assign it to your Resource Group, use any key-value pair for the tag
    - Be sure to use recognisable name and to create the remediation task
- Verify the assignment and check compliance
    - Navigate to the Policy pane from the portal menu, go to Compliance
    - Find your assignment and open details
    - Check if there is a remediation task already running, if not, create one, if yes, wait 🙂
    - The task may take 15-20 minutes to complete, monitor it occasionally
    - Once the task completes, check the resources in your resource group, verify the tag
- Clean up - remove your test user and the resources which you just created
