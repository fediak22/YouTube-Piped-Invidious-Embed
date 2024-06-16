# Replace YouTube Player with Piped/Invidious Embed

This userscript replaces the default YouTube video player with an embedded player from either Piped or Invidious. It enhances privacy and allows for better customization of the video experience.

## Features

- **Preferred Instances**: Switch between Piped and Invidious instances.
- **Quality Options**: Utilizes DASH for improved quality options.
- **Customizable Iframe**: Includes rounded corners, no borders, and shadow effects for a polished look.
- **Auto Replace**: Automatically replaces the player on page load and AJAX navigation.
- **Mute and Pause Original**: Mutes and pauses the original YouTube player to prevent playback conflicts.

## Installation

### Step 1: Install a Userscript Manager
To use this userscript, you need to have a userscript manager installed in your browser. Some popular options include:
- [Tampermonkey](https://www.tampermonkey.net/)
- [Greasemonkey](https://www.greasespot.net/)
- [Violentmonkey](https://violentmonkey.github.io/)

### Step 2: Add the Script
1. Open your userscript manager dashboard.
2. Create a new userscript.
3. Copy and paste the script into the editor:

### Step 3: Save and Activate the Script
1. Save the script in your userscript manager.
2. Make sure the script is enabled.

## Usage

### Switching Between Piped and Invidious
To switch the preferred instance between Piped and Invidious:
1. Open the script in your userscript manager.
2. Find the line: `const preferredInstance = invidiousInstance;`
3. Change `invidiousInstance` to `pipedInstance` if you prefer to use Piped.

### How It Works
- The script runs automatically on YouTube video pages.
- It replaces the YouTube player with the chosen embedded player.
- The script ensures the replacement occurs within the first 10 seconds of page load or navigation to a new video.

## Contributing
Feel free to fork the repository and submit pull requests if you have improvements or bug fixes.

Enjoy a seamless and customizable video experience on YouTube with Piped or Invidious embedded players!
