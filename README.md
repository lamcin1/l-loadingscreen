# FiveM Loading Screen

A customizable and interactive loading screen for FiveM that features an engaging user interface with background video, volume control, social media links, a team modal, and a useful tips section.

## Features:
- **Background Video**: Set any MP4 video as the background.
- **Server Logo**: Displays the server logo at the top left of the screen.
- **Volume Control**: Adjust the volume of the background video and mute it as needed.
- **Social Media Links**: Add buttons linking to your social media pages (TikTok, Discord, YouTube).
- **Tip Box**: Displays random tips that change every 5 seconds.
- **Team Modal**: Shows a list of your team, loaded from an external `team.json` file.
- **Interactive Buttons**: Toggle the visibility of the UI with a single button.
- **Responsive Design**: The loading screen adapts to different screen sizes, including mobile devices.

## Technologies Used:
- **HTML5**: Structure of the loading screen.
- **CSS3 / TailwindCSS**: Styling and responsive layout via Tailwind CDN.
- **JavaScript**: Logic for volume control, random tips, and modal behavior.
- **JSON**: Used to manage team data and tips.
- **FiveM (Cfx.re)**: Game modification framework for integration.

## Installation:
1. Drag and Drop this resource in your fivem resource directory
2. Make sure to add or replace `video/background.mp4` and `img/server_logo.png`.
3. Customize `team.json` and `tipps.json` with your desired information.
   
## Customization:
- **Logo**: Replace `server_logo.png` with your own server logo.
- **Video**: Add `background.mp4` with your desired background video.
- **Team Data**: Edit the `team.json` to display team members with name, image, and role.
- **Tips**: Edit the `tipps.json` to add custom tips that will be shown during the loading process.

## License:
This project is licensed under the [GNU General Public License v3.0 (GPL-3.0)](LICENSE). You can freely use, modify, and distribute it under the terms of this license.

