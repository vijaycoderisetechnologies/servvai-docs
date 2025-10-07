---
title: Edit Events
parent: Events
nav_order: 4
---
# Configuring Recurring Events

!!! info "⚡ Premium Feature"
    This feature is available only on Premium plans.

Recurring events allow you to automatically repeat an event on a **daily**, **weekly**, or **monthly** basis.  

## Daily Recurrence
The **Daily Recurrence** option allows you to repeat an event every set number of days.  

### Enable Recurrence
- Go to your event creation or editing page.  
- Locate the **Recurrence** section.  
- Click the **Recurring** option to enable recurrence settings.

<img src="{{ site.baseurl }}/assets/images/reccuring1.png" alt="Servv Event Settings" width="600" style="max-width: 100%; height: auto;" />

### Select Daily Recurrence
- From the recurrence type options (Daily, Weekly, Monthly), select **Daily**.

<img src="{{ site.baseurl }}/assets/images/reccuring2.png" alt="Servv Event Settings" width="600" style="max-width: 100%; height: auto;" />

### Set Repeat Interval
- You will see the option **Repeat every**.  
- Use the dropdown menu to select how many days apart the event should repeat.  
  - Example:  
    - Select `1` → Event repeats **every day**.  
    - Select `2` → Event repeats **every 2 days**.  
    - Select `3` → Event repeats **every 3 days**, and so on.

<img src="{{ site.baseurl }}/assets/images/reccuring3.png" alt="Servv Event Settings" width="600" style="max-width: 100%; height: auto;" />    

### Choose an End Condition
You must decide when the recurrence should stop. Two options are available:

- **End by date**  
  - Select the **End date by** option.  
  - A date picker will appear.  
  - Choose a specific date when the event should stop repeating.  
  - Example: If today is 1st January and you select 10th January, the event will repeat daily until 10th January.

- **End after number of occurrences**  
  - Select the **End date after** option.  
  - A dropdown menu will appear with numeric values (1, 2, 3 …).  
  - Choose the number of times the event should repeat.  
  - Example: If you select `3`, the event will occur **3 times** and then stop automatically.

<img src="{{ site.baseurl }}/assets/images/reccuring4.png" alt="Servv Event Settings" width="600" style="max-width: 100%; height: auto;" />  

### Example Scenarios
- **Example 1**  
  - Repeat every: `1` day  
  - End after: `5 occurrences`  
  - Result → Event will run for 5 days in a row and then end.

- **Example 2**  
  - Repeat every: `2` days  
  - End date by: `31st March`  
  - Result → Event will run every alternate day until 31st March.

### Key Notes
- **Daily recurrence is best for events that happen regularly each day or every few days.**  
- Always set an **end condition** (date or number of occurrences) to avoid unintended endless recurrence.  

---

## Weekly Recurrence
The **Weekly Recurrence** option allows you to repeat an event every set number of weeks and on specific weekdays.  

### Enable Recurrence
- Go to your event creation or editing page.  
- Locate the **Recurrence** section.  
- Click the **Recurring** option to enable recurrence settings.

### Select Weekly Recurrence
- From the recurrence type options (Daily, Weekly, Monthly), select **Weekly**.

<img src="{{ site.baseurl }}/assets/images/reccuring9.png" alt="Servv Event Settings" width="600" style="max-width: 100%; height: auto;" />

### Set Repeat Interval
- You will see the option **Repeat every**.  
- Use the dropdown menu to select how many weeks apart the event should repeat.  
  - Example:  
    - Select `1 week` → Event repeats **every week**.  
    - Select `2 weeks` → Event repeats **every 2 weeks**.  
    - Select `3 weeks` → Event repeats **every 3 weeks**, and so on.

<img src="{{ site.baseurl }}/assets/images/reccuring9.png" alt="Servv Event Settings" width="600" style="max-width: 100%; height: auto;" />    

### Choose Weekdays
- In the **Occurs on** section, select the checkboxes for the weekdays when the event should happen.  
- Example: Select **Monday, Wednesday, Friday** → Event will occur on those three days each week.

<img src="{{ site.baseurl }}/assets/images/reccuring5.png" alt="Servv Event Settings" width="600" style="max-width: 100%; height: auto;" />

### Choose an End Condition
You must decide when the recurrence should stop. Options are the same as daily recurrence:

- **End by date** → Pick a calendar date when the repetition stops.  
- **End after number of occurrences** → Choose how many times the event should repeat before ending.

### Example Scenarios
- **Example 1**  
  - Repeat every: `1 week`  
  - Occurs on: Monday, Wednesday  
  - End after: `4 occurrences`  
  - Result → Event will occur 4 times (on Mondays and Wednesdays) before ending.

- **Example 2**  
  - Repeat every: `2 weeks`  
  - Occurs on: Friday  
  - End date by: `30th April`  
  - Result → Event will occur every alternate Friday until 30th April.

### Key Notes
- **Weekly recurrence is ideal for events that happen on fixed weekdays.**  
- You can select multiple weekdays in the same week.

---

## Monthly Recurrence
The **Monthly Recurrence** option allows you to repeat an event every set number of months. You can choose either a specific date of the month or a pattern like “first Monday.”  

### Enable Recurrence
- Go to your event creation or editing page.  
- Locate the **Recurrence** section.  
- Click the **Recurring** option to enable recurrence settings.

### Select Monthly Recurrence
- From the recurrence type options (Daily, Weekly, Monthly), select **Monthly**.

### Set Repeat Interval
- You will see the option **Repeat every**.  
- Use the dropdown menu to select how many months apart the event should repeat.  
  - Example:  
    - Select `1 month` → Event repeats **every month**.  
    - Select `2 months` → Event repeats **every 2 months**.  
    - Select `3 months` → Event repeats **every 3 months**, and so on.

<img src="{{ site.baseurl }}/assets/images/reccuring6.png" alt="Servv Event Settings" width="600" style="max-width: 100%; height: auto;" />    

### Choose a Monthly Pattern
Two options are available:

- **Occurs on a specific day of the month**  
  - Select a date (1, 2, 3 … up to 31).  
  - Example: Choosing `15` → Event occurs on the 15th of each month.

<img src="{{ site.baseurl }}/assets/images/reccuring7.png" alt="Servv Event Settings" width="600" style="max-width: 100%; height: auto;" />  

- **Occurs on a specific day of the week**  
  - Two dropdowns appear:  
    - First dropdown: Select **First, Second, Third, or Fourth**.  
    - Second dropdown: Select a day of the week (Sunday, Monday, etc.).  
  - Example: Select `First Monday` → Event occurs on the first Monday of each month.

<img src="{{ site.baseurl }}/assets/images/reccuring8.png" alt="Servv Event Settings" width="600" style="max-width: 100%; height: auto;" />  

### Choose an End Condition
- **End by date** → Select a calendar date when the event should stop repeating.  
- **End after number of occurrences** → Choose how many times the event should repeat before ending.

### Example Scenarios
- **Example 1**  
  - Repeat every: `1 month`  
  - Occurs on: Day 10 of each month  
  - End after: `6 occurrences`  
  - Result → Event will occur on the 10th of each month, six times total.

- **Example 2**  
  - Repeat every: `2 months`  
  - Occurs on: Second Friday  
  - End date by: `31st December`  
  - Result → Event will occur on the second Friday every 2 months until 31st December.

### Key Notes
- **Monthly recurrence is useful for billing cycles, monthly meetings, or reminders.**  
- You can choose either a **fixed date** or a **weekday pattern**.

### Need Help?

If you encounter issues or need further assistance:

- Visit our [FAQs](https://support.servv.ai/faq)
- Submit a [Support Request Form](https://servv.ai/contact)
- Use the live chat feature directly from your Servv.ai WordPress dashboard

We're here to support you every step of the way.