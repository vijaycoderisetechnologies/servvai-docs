---
title: Email Templates
parent: Notifications
nav_order: 1
---
# Email Template Configuration

!!! info "⚡ Premium Feature"
    The **Notifications** feature is available only on Premium plans.

This document provides a comprehensive guide to configuring **Email Templates** within the **Servv AI WordPress Plugin** for sending notifications to event members who have purchased or registered for events. It is designed to help WordPress administrators and site managers effectively manage email notifications for events created via the Servv platform.

### Navigate to Notifications

In the **Servv AI** menu, select **Notifications**. **Email Templates** Dashboard open. to view and manage available templates for event member notifications.

<img src="{{ site.baseurl }}/assets/images/notification1.png" alt="Servv" width="200" style="max-width: 100%; height: auto;" />

### Select a Template 
In the **Email Templates** section, locate the **Template Name** dropdown. Click the dropdown to view all available email templates designed for event members. Select the desired template from the dropdown to begin editing the notification content for event members.

<img src="{{ site.baseurl }}/assets/images/notification2.png" alt="Servv" width="700" style="max-width: 100%; height: auto;" />

## Available Template Names

The following email templates are available for customization to communicate with event members who have purchased or registered for events:

- In-person Event - Booking
- In-person Event - Updated
- In-person Event - Cancelled
- In-person Event - Reminder
- In-person Event - Remove Registrant
- Virtual Event - Booking
- Virtual Event - Updated
- Virtual Event - Cancelled
- Virtual Event - Reminder
- Virtual Event - Remove Registrant
- Virtual Event - Finished
- In-person Event - Finished
- In-person Event - Booking (Member Notification)
- Virtual Appointment - Booking (Member Notification)
- Virtual Event - Booking (Member Notification)
- In-person Event - Members Reminder
- Virtual Event - Members Reminder

## Default Email Subject Mapping

Each template is preconfigured with a default subject line, dynamically populated based on the event type to ensure clear communication with event members:

| Template Name                                      | Default Email Subject                                |
|---------------------------------------------------|------------------------------------------------------|
| In-person Event - Booking                          | `{{event_name}} - {{store_name}}`                    |
| In-person Event - Updated                          | `{{event_name}} information has been updated`        |
| In-person Event - Cancelled                        | `{{event_name}} has been cancelled`                  |
| In-person Event - Reminder                         | `{{event_name}} reminder email`                      |
| In-person Event - Remove Registrant                | `{{event_name}} registration has been cancelled`     |
| Virtual Event - Booking                            | `{{event_name}} Confirmation`                        |
| Virtual Event - Updated                            | `{{event_name}} has been updated`                    |
| Virtual Event - Cancelled                          | `{{event_name}} has been cancelled`                  |
| Virtual Event - Reminder                           | `{{event_name}} reminder email`                      |
| Virtual Event - Remove Registrant                  | `{{event_name}} registration has been cancelled`     |
| Virtual Event - Finished                           | `{{event_name}} Finished`                            |
| In-person Event - Finished                         | `{{event_name}} Finished`                            |
| In-person Event - Booking (Member Notification)    | `{{event_name}} - New booking`                       |
| Virtual Appointment - Booking (Member Notification)| `{{event_name}} - New booking`                       |
| Virtual Event - Booking (Member Notification)      | `{{event_name}} - New booking`                       |
| In-person Event - Members Reminder                 | `{{event_name}} \| Your Event Details Inside!`       |
| Virtual Event - Members Reminder                   | `{{event_name}} \| Your Event Details Inside!`       |

## Supported Template Variables

The Servv AI WordPress Plugin supports dynamic variables to personalize email content for event members. Use the following variables to insert event-specific information relevant to participants:

| Variable                        | Description                                    |
|--------------------------------|------------------------------------------------|
| `{{category_details}}`         | Category details                              |
| `{{category}}`                 | Category of event                             |
| `{{custom_field_1_name}}`      | Custom field 1 name                           |
| `{{custom_field_1_value}}`     | Custom field 1 value                          |
| `{{custom_field_2_name}}`      | Custom field 2 name                           |
| `{{custom_field_2_value}}`     | Custom field 2 value                          |
| `{{customer_name}}`            | Customer name                                 |
| `{{customer_email}}`           | Customer email                                |
| `{{date}}`                     | Date of event                                 |
| `{{event_name}}`               | Event name                                    |
| `{{location_details}}`         | Location details                              |
| `{{location_hours}}`           | Location operational hours                    |
| `{{location}}`                 | Location of event                             |
| `{{members_list}}`             | Event members info list                       |
| `{{store_email}}`              | Store contact email                           |
| `{{store_name}}`               | Store name                                    |
| `{{time}}`                     | Time of event                                 |
| `{{zoom_link}}`                | Link to Zoom event (for virtual events)       |
| `{{member_name}}`              | Member name                                   |
| `{{answers}}`                  | List of registrants' answers to questions     |
| `{{registrants}}`              | Event registrants list                        |
| `{{waiting_list}}`             | Event waiting list                            |

## Editing Email Templates

The Servv AI WordPress Plugin provides a user-friendly interface for customizing email templates to communicate effectively with event members:

### Enter Editing Mode
After selecting a template, use the built-in **Rich Text Editor** for standard formatting (e.g., bold, italics, lists).
For advanced customization, switch to the **HTML Editor** to directly edit the HTML code for tailored notifications.

<img src="{{ site.baseurl }}/assets/images/notification3.1.png" alt="Servv" width="700" style="max-width: 100%; height: auto;" /> <img src="{{ site.baseurl }}/assets/images/notification3.2.png" alt="Servv" width="700" style="max-width: 100%; height: auto;" />

**Note**: Ensure that any custom HTML is compatible with common email clients (e.g., Gmail, Outlook) to avoid rendering issues for event members.

### Preview the Email
Use the **Preview** at the bottom of the template editor to view how the email will appear to event members.
Verify that dynamic variables (e.g., `{{event_name}}`) are correctly populated and that formatting is consistent across email clients.

<img src="{{ site.baseurl }}/assets/images/notification4.png" alt="Servv" width="700" style="max-width: 100%; height: auto;" />

After editing, click the **Save** button to store your changes.
The plugin syncs the updated template with the servv.io platform, ensuring consistent notifications are sent to event members.


---

###  Need Help?

If you're stuck or need further assistance:

- Check our [FAQs](https://support.servv.ai/faq)
- Reach out via [Support Request Form](https://servv.ai/contact)
- Chat with us directly from your Servv dashboard

We're here to help — every step of the way.