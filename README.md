# Mod Tools

A collection of lightweight web tools designed to assist streamers and moderators with channel management. Currently featuring a Twitch User ID lookup utility, with additional moderation tools in development.

## Features

- Log in with Twitch (OAuth)
- Enter a Twitch username to retrieve the corresponding user ID
- Designed to be easily extended with additional moderation tools

## Setup

1. Clone the repository:

   ```sh
   git clone https://github.com/zephsinx/modtools.git
   cd modtools
   ```

2. (Optional) Serve the app locally:

   ```sh
   python serve.py
   ```

   Then open `http://localhost:8000` in your browser.

## Usage

1. Open the app in your browser.
2. Log in with your Twitch account.
3. Use the available moderation tools (e.g., enter a Twitch username and click "Get User ID" to retrieve the user ID).

## Configuration

- Update the `CLIENT_ID` and `REDIRECT_URI` in `constants.js` if you use your own Twitch app credentials.
