
- Adding custom branding requires you to have either Azure AD Premium 1, Premium 2, or Office 365 (for Office 365 apps) license.
- [Azure AD roles](https://learn.microsoft.com/en-us/training/modules/implement-initial-configuration-of-azure-active-directory/3-configure-manage-roles)
    - Global admin
    - User admin
    - Billing admin
- If a Global Administrator elevates their access by choosing the Access management for Azure resources switch in the Azure portal, the Global Administrator will be granted the User Access Administrator role (an Azure role) on all subscriptions for a particular tenant. The User Access Administrator role enables the user to grant other users access to Azure resources. This switch can be helpful to regain access to a subscription.
- In Azure AD, using a single tenant if you assign a user any administrator role, they're now an admin over every user in the tenant. Administrative units are containers created to solve for this challenge in Azure AD if you want a User Administrator to be able to manage only a specific set of users and group. An administrative unit can contain only users and groups. 

## Administrative Units

You can have users in the following roles to manage your administrative unit:
* 		Authentication administrator
* 		Groups administrator
* 		Helpdesk administrator
* 		License administrator
* 		Password administrator
* 		User administrator

## Delegate app administration

* 		The Application Administrator role, which grants the ability to manage all applications in the directory, including registrations, single sign-on settings, user and group assignments and licensing, Application Proxy settings, and consent. It doesn't grant the ability to manage Conditional Access.
* 		The Cloud Application Administrator role, which grants all the abilities of the Application Administrator, except it doesn't grant access to Application Proxy settings (because it has no on-premises permission).

## Delegate app registration

* 		Set Users can register applications to No in User settings
* Set Users can consent to applications accessing company data on their behalf To No in User settings under Enterprise apps
* 		Assign the user to the Application Developer role

## Delegate app ownership

There are two app owner roles:
* 		The Enterprise Application Owner role grants the ability to manage the ‘enterprise applications that the user owns, including single sign-on settings, user and group assignments, and adding more owners. It doesn't grant the ability to manage Application Proxy settings or Conditional Access.
* 		The Application Registration Owner role grants the ability to manage application registrations for app that the user owns, including the application manifest and adding other owners.

