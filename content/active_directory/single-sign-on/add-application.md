---
title: Add an enterprise application"
linkTitle: "Add Application"
weight: 1
type: docs
description: >
    you use the Azure Active Directory Admin Center to add an enterprise application to your Azure Active Directory (Azure AD) tenant. Azure AD has a gallery that contains thousands of enterprise applications that have been pre-integrated. Many of the applications your organization uses are probably already in the gallery. This uses the application named Azure AD SAML Toolkit as an example, but the concepts apply for most enterprise applications in the gallery.
tags: ["Azure"]
---

### Prerequisites

To add an enterprise application to your Azure AD tenant, you need:

- An Azure AD user account.

- One of the following roles: Global Administrator, Cloud Application Administrator, or Application Administrator.

### Add an enterprise application

To add an enterprise application to your tenant:

1. Go to the Azure Active Directory Admin Center and sign in using one of the roles listed in the prerequisites.

1. In the left menu, select Enterprise applications. The All applications pane opens and displays a list of the applications in your Azure AD tenant.

1. In the Enterprise applications pane, select New application.

1. The Browse Azure AD Gallery pane opens and displays tiles for cloud platforms, on-premises applications, and featured applications. Applications listed in the Featured applications section have icons indicating whether they support federated single sign-on (SSO) and provisioning. Search for and select the application. In this example, Azure AD SAML Toolkit is being used.    {{% figure src="images/active-directory/ad-saml-addapplication.png" alt="Azure Add Application" %}}

1. Enter a name that you want to use to recognize the instance of the application. For example, Azure AD SAML Toolkit 1.

1. Select Create.
