# Module 1 Lab

Created: Jan 5, 2021 10:43 AM
Tags: AZ-104

# Explore the Azure Portal

- Try the dark theme
- Find your portal menu setting
- Explore All Services and Favourites

# Manage an Azure AD tenant

- Create a new Azure AD tenant
    - Create a resource option from the portal menu
    - Type in Azure Active Directory
    - Create
    - Fill out the required options and create
- Switch between Azure AD directories - the default one and the one you just created, explore both.
    - Try switching back and forth. See what happens.
    - Explore the Azure Active Directory tab from the menu
    - Make sure to switch to your new azure AD tenant
    - Note what is your role
- Create two users in your new Azure AD tenant.
    - Create two test users, Jane Doe and John Smith.
    - Fill out the following properties for the new users:
        - Location (go for Netherlands)
        - Job Title (use different values)
        - Department (use the same value)

- Create two new groups - one with the static assignment and one with dynamic assignment based  on the Department property
    - Create a new security group with static assignment
    - Add the first user to the group
    - Grant the group "Security Administrator" permissions in Azure AD
    - Create another security group with dynamic assignment, use the Department property as the criteria
    - Verify the configuration

# Test your new user

- Log in with the first of the new users
    - Open a Private/Incognito web browser and navigate to the Azure Portal
    - Log in with the credentials of the first user (the one which is a member of the static group)
- Invite a user with Azure AD B2B
    - Open the Azure AD tab from the portal menu
    - Naviate to Users
    - Invite someone (for example me) as a guest user
