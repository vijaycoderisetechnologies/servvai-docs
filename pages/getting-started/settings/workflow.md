---
title: Workflow
parent: Settings
nav_order: 6
---
# Trigger Workflow Settings

This feature allows you to connect your servv ai with **n8n** or other automation tools.  
By enabling these triggers, you can automatically start workflows when certain actions occur — such as creating events, receiving bookings, or canceling bookings.

---

## Event Created Trigger

**Description:**  
Enable this option to trigger an n8n workflow whenever a **new event** is created in WordPress.

**How It Works:**  
Once enabled, servv ai will send event data to the configured n8n webhook URL using a `POST` request.

---

## New Booking Trigger

**Description:**  
Enable this option to trigger a workflow whenever a **new booking** is made for an event.

**How It Works:**  
When a user books an event, servv ai sends booking details to your configured n8n webhook endpoint.

**Configuration:**

---

## Canceled Booking Trigger

**Description:**  
Enable this option to trigger a workflow whenever a **booking is canceled** by a user or admin.

**How It Works:**  
When a booking is canceled, servv ai sends a cancellation request to your n8n endpoint.

## Configuration

| Setting | Description | Example |
|----------|--------------|----------|
| **HTTP Method** | The method used to send data to n8n. | `POST` |
| **Endpoint URL** | The n8n webhook URL to receive cancellation data. | *(Add your webhook URL here)* |
| **Secret** | A secret key used for validation. | *(Enter your secret key)* |

---

## How to Use

1. Go to your **WordPress Dashboard → Servv AI → Setting → Workflow**. 

<img src="{{ site.baseurl }}/assets/images/workflow.png" alt="Servv" width="700" style="max-width: 100%; height: auto;" />

2. Toggle **ON** the trigger you want to use:
   - Event Created
   - New Booking
   - Canceled Booking  

3. Add your **Webhook URL** and **Secret** (from your n8n workflow). 

<img src="{{ site.baseurl }}/assets/images/triggeres.png" alt="Servv" width="700" style="max-width: 100%; height: auto;" />

4. Save the settings.  

5. Test by performing the related action in servv ai — the workflow in n8n should trigger automatically.

---

## Learn How to Create an n8n Workflow

If you’re new to **n8n**, follow the official documentation to learn how to create a webhook-based workflow:  
[n8n Webhook Node Documentation](https://docs.n8n.io/integrations/builtin/core-nodes/n8n-nodes-base.webhook/)

This guide explains how to:
- Create a new workflow in n8n  
- Add a **Webhook** node  
- Configure the **HTTP Method** and **Response Mode**  
- Copy your webhook URL and use it inside the plugin settings  

---

## Notes

- Make sure your n8n webhook URL is **publicly accessible**.  
- The **Secret** value in servv ai must match the **Secret** configured in your n8n workflow.  
- Each trigger operates independently — you can enable one, two, or all triggers.  
- These webhooks help automate processes like sending notifications, or creating reports.

---

**Thank you for using Servv AI.**
