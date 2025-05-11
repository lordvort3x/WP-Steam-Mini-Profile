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
```
## Customization

The plugin includes the following customization options:

---
### Custom Fonts:

- Uses the BF_Modernista-Regular.ttf font for a modern gaming aesthetic.

- Profile Picture Border Glow:

   Blue: Online,
   Green: In-game,
   Gray: Offline

- Profile Button:
A hover-activated button to view the full Steam profile.

## Requirements
- WordPress 5.0 or higher.
- A valid Steam API Key.
- Your unique Steam ID (find it in your Steam profile URL).

## Example Styling

Add the Steam Mini Profile to any post, page, or widget using the shortcode, and it will display a styled profile like this:

![alt text](https://lordvort3x.se/wp-content/uploads/2025/05/image_2025-05-11_202413409.png "Img 1")

Image for illustration purposes only.

## Development

### Files Overview
``` steam-profile-plugin.php```: Main plugin file, handles initialization and shortcode.

```includes/steam-api.php```: Handles communication with the Steam Web API.

```assets/style.css```: Contains the styling for the mini-profile.

```assets/script.js```: Adds interactivity, such as hover effects for the profile button.

## Contributing
Feel free to fork this repository, make your changes, and submit a pull request. Contributions are always welcome!

## License
This plugin is licensed under the MIT License.
You are free to use, modify, and distribute this plugin under the terms of the license.
