# Dynatrace_azure_sso_integration


**Prerequisites**

To get started, you need the following items:

An Azure AD subscription. If you don't have a subscription, you can get a free account.
Dynatrace single sign-on (SSO) enabled subscription.

Steps:
======
1. Add Dynatrace from the gallery to Azure
2. Configure Azure AD SSO
3. Configure Dynatrace SSO
4. Test SSO

**1. Add Dynatrace from the gallery**

To configure the integration of Dynatrace into Azure AD, you need to add Dynatrace from the gallery to your list of managed SaaS apps.

- Sign in to the Azure portal using either a work or school account, or a personal Microsoft account.
- On the left navigation pane, select the Azure Active Directory service.

<img width="1550" alt="image" src="https://user-images.githubusercontent.com/74225291/211815104-df956c6b-bdeb-48c8-b915-c2baf3c2d0c8.png">

- Navigate to Enterprise Applications, and then select All Applications.
- To add new application, select New application.

<img width="1693" alt="image" src="https://user-images.githubusercontent.com/74225291/211815412-0b26a326-dc70-48ca-ae4f-933c6ccb6927.png">

- In the Add from the gallery section, type Dynatrace in the search box.
- Select Dynatrace from results panel and then add the app. Wait a few seconds while the app is added to your tenant.

<img width="1744" alt="image" src="https://user-images.githubusercontent.com/74225291/211815497-46aba4f1-60e1-403b-becc-c15bb8ddeb8e.png">

**Configure and test Azure AD SSO for Dynatrace**

Configure and test Azure AD SSO with Dynatrace using a test user called Vihan.D. For SSO to work, you need to establish a link relationship between an Azure AD user and the related user in Dynatrace.

To configure and test Azure AD SSO with Dynatrace, complete the following building blocks:

- Configure Azure AD SSO - to enable your users to use this feature.
- Create an Azure AD test user - to test Azure AD single sign-on with Vihan.
- Assign the Azure AD test user - to enable Vihan.D to use Azure AD single sign-on.
- Configure Dynatrace SSO - to configure the single sign-on settings on application side.
- Create Dynatrace test user - to have a counterpart of Vihan.D in Dynatrace that is linked to the Azure AD representation of user.
- Test SSO - to verify whether the configuration works.


**2. Configure Azure AD SSO**

Follow these steps to enable Azure AD SSO in the Azure portal.

- In the Azure portal on the Dynatrace application integration page, find the Manage section and select single sign-on.
- On the Select a single sign-on method page, select SAML.

<img width="921" alt="image" src="https://user-images.githubusercontent.com/74225291/211964871-3923ef2e-b3d2-491f-8277-7174d8296e3c.png">

- On the Set up single sign-on with SAML page, click the pencil icon for Basic SAML Configuration to edit the settings.



<img width="1544" alt="image" src="https://user-images.githubusercontent.com/74225291/211816424-72b63a14-f10b-4e0d-9457-2393920c6fdf.png">

<img width="810" alt="image" src="https://user-images.githubusercontent.com/74225291/211819483-53028b3f-bf81-4ac6-a45f-f1062db1b031.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/74225291/211819575-6b6271b1-f613-4f69-94d3-b73ce72cf0da.png">



Azure SAML configuration for Dynatrace

