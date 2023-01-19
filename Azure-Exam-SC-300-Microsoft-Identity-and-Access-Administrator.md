
- Adding custom branding requires you to have either Azure AD Premium 1, Premium 2, or Office 365 (for Office 365 apps) license.
- [Azure AD roles](https://learn.microsoft.com/en-us/training/modules/implement-initial-configuration-of-azure-active-directory/3-configure-manage-roles)
    - Global admin
    - User admin
    - Billing admin
- If a Global Administrator elevates their access by choosing the Access management for Azure resources switch in the Azure portal, the Global Administrator will be granted the User Access Administrator role (an Azure role) on all subscriptions for a particular tenant. The User Access Administrator role enables the user to grant other users access to Azure resources. This switch can be helpful to regain access to a subscription.
- In Azure AD, using a single tenant if you assign a user any administrator role, they're now an admin over every user in the tenant. Administrative units are containers created to solve for this challenge in Azure AD if you want a User Administrator to be able to manage only a specific set of users and group. An administrative unit can contain only users and groups. 
