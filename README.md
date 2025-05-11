# WP-Steam-Mini-Profile
Wordpress Plugin - Steam Mini Profile 

The **Steam Mini Profile Plugin** is a WordPress plugin that displays a visually styled Steam mini-profile on your website. It provides an overview of your Steam profile, including recent activity, games owned, and achievements. The plugin is highly customizable and perfect for gamers who want to showcase their Steam stats online.

---

## Features

- **Steam Profile Information**:  
  Displays your Steam username, profile picture, status (online, offline, or in-game), and Steam level.  

- **Recently Played Games**:  
  Shows your recently played games with details like playtime.  

- **Achievements**:  
  Highlights achievements for specific games.  

- **Customizable Design**:  
  Styled to look like a Steam mini-profile, with glowing borders indicating your status (blue for online, green for in-game, gray for offline).  

---

## Installation

1. Download the plugin or clone this repository.  
2. Upload the plugin folder to the `wp-content/plugins` directory of your WordPress site.  
3. Activate the plugin via the **Plugins** page in the WordPress admin dashboard.

---

## Usage

### Shortcode

Use the `[steam_profile]` shortcode to display the mini-profile anywhere on your site. You can customize the shortcode with the following attributes:

```php
[steam_profile steam_id="<STEAM_ID>" api_key="YOUR_STEAM_API_KEY"]
