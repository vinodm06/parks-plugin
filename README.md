# City Of Mississauga Parks Management Plugin

This plugin allows admin users to manage and filter parks, their locations, and facilities. It provides a custom post type for parks, a taxonomy for park facilities, and an AJAX-powered filter for users to search parks based on location and facilities.

## Features
- Custom post type for parks
- Custom taxonomy for park facilities
- AJAX-based filtering of parks by location and facilities
- Meta boxes for park details including location, weekday and weekend hours

## Installation

### 1. Upload the Plugin
To install the plugin, follow these steps:

1. Download the plugin files as a ZIP file from the source.
2. Go to your WordPress admin dashboard.
3. Navigate to **Plugins > Add New**.
4. Click **Upload Plugin**.
5. Choose the downloaded ZIP file and click **Install Now**.
6. After installation, click **Activate**.

### 2. Manual Installation (Alternative)
If you prefer to install the plugin manually:

1. Upload the plugin folder to your WordPress installation’s `wp-content/plugins/` directory.
2. Go to the WordPress admin panel and navigate to **Plugins > Installed Plugins**.
3. Find the **Mississauga Parks Plugin** in the list and click **Activate**.

### 3. Activate the Plugin

### 4. Using the Plugin
1. You will see a new **Parks** menu item in your WordPress admin dashboard. You can add and manage parks from here.
2. To display the parks on a page, use the following shortcode:
   ```text
   [city_parks]

