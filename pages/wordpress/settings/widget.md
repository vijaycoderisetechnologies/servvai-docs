---
title: Widget
parent: Settings
nav_order: 4
---
# Servv Widget Shortcode Guide

The Servv plugin allows you to add a fully customizable **Event Widget** anywhere on your WordPress website using a simple shortcode.

---

## How to Add the Widget 

Follow these steps to display the widget:

1. **Open the page or post** where you want the widget to appear.  
2. Click the **`+` button** to add a new block and choose **Shortcode**.  
3. Paste the following shortcode inside the block: 

  [servvai style="cyan" preset="light"]

<img src="{{ site.baseurl }}/assets/images/shortcode.png" alt="Servv" width="600" style="max-width: 100%; height: auto;" />

- `style` defines the widget’s color theme.  
- `preset` defines the brightness mode (`light` or `dark`).  

## Widget Style Options

You can customize the widget appearance by changing the `style` and `preset` attributes in the shortcode.

**Available Styles (`style`):**
- `blue`  
- `green`  
- `orange`  
- `red`  
- `purple`  
- `light-red`  
- `cyan`  

**Available Presets (`preset`):**
- `light`  
- `dark`  

**Example Shortcodes:**

- Light blue theme:  
[servvai style="blue" preset="light"]

<img src="{{ site.baseurl }}/assets/images/presetlight.png" alt="Servv" width="400" style="max-width: 100%; height: auto;" />

- Dark orange theme:  
[servvai style="orange" preset="dark"]

<img src="{{ site.baseurl }}/assets/images/presetdark.png" alt="Servv" width="400" style="max-width: 100%; height: auto;" />

## Filtered Widget Shortcodes

Servv AI also allows you to display events filtered by **Location**, **Language**, **Member**, or **Category** directly through shortcode.

This feature is useful if you want to show only specific types of events on a page — for example, events happening in a certain location or belonging to a specific category.

### Single Filter Usage

You can apply any one of the filters below individually:

- **Location-based events:**
  [servvai location="pune"]

- **Language-based events:**
  [servvai language="english"]

- **Category-based events:**
[servvai category="webinar"]

- **Member-based events:**
  [servvai member="john-doe"]

### Multiple Filter Values
You can include multiple values for the same filter by separating them with a `$` symbol.

Examples:

- **Multiple locations:**
  [servvai location="pune$mumbai$delhi"]

- **Multiple languages:**
  [servvai language="english$spanish"]

- **Multiple categories:**
  [servvai category="webinar$workshop$conference"]

- **Multiple members:**
  [servvai member="john-doe$jane-smith"]

### Combined Filters
You can also combine multiple filters together in one shortcode to narrow down the events shown in the widget.

Example — Show only English webinars happening in Canada:

[servvai location="canada" language="english" category="webinar"]

You can mix and match any combination of `location`, `language`, `category`, and `member` filters.
        
# Widget Settings

## Accessing Widget Settings
**Navigate to the Serve.AI Sidebar**: Locate the **Settings** option in the Serve.AI menu on the sidebar. In the Settings dashboard, click on the **Widget** section to access the widget configuration options. 

<img src="{{ site.baseurl }}/assets/images/widget1.png" alt="Servv" width="600" style="max-width: 100%; height: auto;" />

The widget settings are divided into four main categories. **Display Mode Options**, **Item Settings**, **Filter Settings**, and **Additional Widget Display Settings**. Each section is described below.

### Display Mode Options
These settings allow you to control how the widget appears on the page, offering two layout options tailored to your preferences.
**Dropdown Menu**:

<img src="{{ site.baseurl }}/assets/images/widget2.png" alt="Servv" width="600" style="max-width: 100%; height: auto;" />

- **Grid**: Displays events in a grid layout.

<img src="{{ site.baseurl }}/assets/images/grid.png" alt="Servv" width="400" style="max-width: 100%; height: auto;" />

- **List**: Displays events in a list format.

<img src="{{ site.baseurl }}/assets/images/list.png" alt="Servv" width="400" style="max-width: 100%; height: auto;" />



**Fluid Grid Checkbox**:
Enable the Fluid Grid checkbox (below the dropdown menu) to make the grid layout responsive, adapting to the screen size for a seamless display.


### Item Settings
This section allows you to configure display limits and default page sizes for items in the widget.

**Grid Item Description Display Limit**:
Set the maximum number of characters or lines to display for item descriptions in the grid layout.

**List Item Description Display Limit**:
Set the maximum number of characters or lines to display for item descriptions in the list layout.

<img src="{{ site.baseurl }}/assets/images/widget3.png" alt="Servv" width="700" style="max-width: 100%; height: auto;" />

**Default Page size**:
Use the dropdown menu to select the default number of items to display per page (e.g., 10, 20, 50, etc.).

### Filter Settings
This section allows you to select which filters are displayed on the event widget, enabling users to refine the events they see.

**Filter Checkboxes**:

- **Location Filter**: Displays a filter for event locations.
-  **Language Filter**: Displays a filter for event languages.
- **Member Filter**: Displays a filter for event members or attendees.
- **Category Filter**: Displays a filter for event categories.

<img src="{{ site.baseurl }}/assets/images/widget4.png" alt="Servv" width="700" style="max-width: 100%; height: auto;" />

**Usage**:
Check the boxes for the filters you want to appear in the event creation form. Unchecked filters will not be visible to users.

<img src="{{ site.baseurl }}/assets/images/widgetcategory.png" alt="Servv" width="700" style="max-width: 100%; height: auto;" />

### Additional Widget Display Settings
This section allows you to control the visibility of various widget components and customize the event widget's appearance.

**Widget Elements Checkboxes**:

- **Show Language Selector**: Displays a language selector in the widget.
- **Show Calendar**: Displays a calendar in the widget.
- **Display Calendar Permanently**: Keeps the calendar visible at all times (requires "Show Calendar" to be enabled).
- **Show Widget Titles**: Displays titles for the widget sections.
- **Show Event Counter**: Displays a counter showing the number of events.
- **View Mode Switch**: Enables a toggle to switch between grid and list views.

**Item Elements Checkboxes**:

- **Show Event Image**: Displays images for events.
- **Show Image as a Square**: Forces event images to display as square thumbnails.
- **Show Separate Badges**: Displays badges (e.g., for event status) separately from other elements.
- **Show Quantity**: Displays the quantity or number of available spots for events.
- **Share Button**: Displays a share button for events.
- **Event Type Badge**: Displays a badge indicating the event type.

<img src="{{ site.baseurl }}/assets/images/widget5.png" alt="Servv" width="400" style="max-width: 100%; height: auto;" />

### Saving Changes
After configuring the desired settings, click the Save button at the top of the Settings panel. All configured settings will be saved and applied.

###  Need Help?

If you're stuck or need further assistance:

- Check our [FAQs](https://support.servv.ai/faq)
- Reach out via [Support Request Form](https://servv.ai/contact)
- Chat with us directly from your Servv dashboard

We're here to help — every step of the way.

