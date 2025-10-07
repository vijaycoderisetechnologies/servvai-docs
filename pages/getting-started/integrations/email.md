---
title:  Email Integration
parent: Integrations
nav_order: 2
---
# Email Integration Guide

This document provides detailed instructions for integrating your email service with your Servv AI account to enable seamless communication for event notifications, confirmations, and reminders. This guide is designed for clarity and ease of use, ensuring a smooth setup process. It assumes familiarity with web-based platforms and basic navigation within a user interface.

> **Note**: Ensure you have the necessary permissions to access the Integration section in Servv AI and valid credentials for the email service you plan to integrate (e.g., Gmail, Outlook, or a custom SMTP provider). Screenshots referenced in this guide are illustrative and may vary slightly based on platform updates.

## Prerequisites
- Active Servv AI account with administrative or integration permissions.
- A valid email account (Gmail, Outlook, or SMTP-based service).
- SMTP server details (for custom email integration).
- Stable internet connection and a supported browser (e.g., Chrome, Firefox, or Edge).

## Navigate to the Integration Section
Log in to your **Servv AI** account.  
Locate the side menu bar on the left-hand side of the interface.  
Click on the **Integration** option to access the integration dashboard.  

*Reference*: The Integration section is typically represented by a dedicated icon or label in the side menu.

<img src="{{ site.baseurl }}/assets/images/integrationsection.png" alt="Servv" width="200" style="max-width: 100%; height: auto;" />

## Select Email Integration
In the integration dashboard, locate the **Email** option. This may be listed among other available integrations.  
Click on the **Email** tile or button to proceed to the email integration setup.

<img src="{{ site.baseurl }}/assets/images/emailintegraion.png" alt="Servv" width="400" style="max-width: 100%; height: auto;" />

## Initiate the Connection
On the Email integration page, locate the **Connect** button.  
Click **Connect** to start the integration process. 

<img src="{{ site.baseurl }}/assets/images/ei1.png" alt="Servv" width="800" style="max-width: 100%; height: auto;" />

If you are integrating via:
- **Gmail or Outlook** – You will be redirected to the provider’s login page.
- **SMTP** – You will be prompted to enter SMTP server details manually.

## Provide Your Email Credentials
If using **Gmail or Outlook**, enter the credentials for the email account you wish to connect.  

Click **Continue** to proceed.

<img src="{{ site.baseurl }}/assets/images/enteremail.png" alt="Servv" width="800" style="max-width: 100%; height: auto;" />

> **Important**: Ensure the email credentials are correct. For SMTP, confirm with your email provider that you have the correct host, port, and security settings. Incorrect details will result in connection errors.

## Review and Authorize Permissions
For Gmail or Outlook integrations, a permissions screen will display, outlining the access Servv AI requires (e.g., sending emails, reading certain metadata for tracking delivery status).  
Review the permissions carefully to ensure you understand the scope of access.  
Click **Continue** to authorize the integration.  

<img src="{{ site.baseurl }}/assets/images/reviewcontinue.png" alt="Servv" width="800" style="max-width: 100%; height: auto;" />

<img src="{{ site.baseurl }}/assets/images/reviewcontinue1.png" alt="Servv" width="800" style="max-width: 100%; height: auto;" />

## Verify Connection Status
Upon successful authorization or SMTP configuration, you will be redirected to the integration dashboard.  
Confirm that the Email integration status displays as **Connected**.  

<img src="{{ site.baseurl }}/assets/images/emailconected.png" alt="Servv" width="800" style="max-width: 100%; height: auto;" />

> **Tip**: If the status does not show as **Connected**, verify your credentials, internet connection, and permissions, then repeat the setup process. Contact Servv.ai support if issues persist.

## Post-Integration Notes
- **Send Test Email**: Use the “Send Test Email” button in the integration dashboard to confirm that messages are being sent successfully.
- **Email Templates**: Customize your event confirmation, reminder, and follow-up email templates in the **Notification Settings** section.
- **Troubleshooting**: If emails are not being delivered, check your spam folder, verify SMTP settings, or ensure that API access is enabled for Gmail/Outlook accounts.

### Need Help?

If you're stuck or need further assistance:

- Check our [FAQs](https://support.servv.ai/faq)
- Reach out via [Support Request Form](https://servv.ai/contact)
- Chat with us directly from your Servv dashboard

We're here to help — every step of the way.
