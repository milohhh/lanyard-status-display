# Discord Status Card (JavaScript)

A lightweight JavaScript script that fetches and displays real-time Discord presence and activity data using the [Lanyard API](https://lanyard.rest/).  
Shows the user's avatar, username, online status, and current activity — including activity images — for seamless integration into any website.

## Features

- Real-time Discord status updates (refreshes every 60 seconds)  
- Displays user avatar and username with discriminator  
- Shows current activity name, details, and timestamps  
- Supports activity images (including Spotify album art)  
- Minimal dependencies — pure JavaScript, no frameworks required

## Usage

1. Include the script in your HTML page or import it as a module.

2. Add an HTML container element with the ID `discord-status` where the status will render:

```html
<div id="discord-status"></div>
