# Twitch User ID Lookup

A simple web tool to look up Twitch user IDs by username using the Twitch API and OAuth authentication.

## Features

- Log in with Twitch (OAuth)
- Enter a Twitch username to retrieve the corresponding user ID

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
3. Enter a Twitch username and click "Get User ID" to retrieve the user ID.

## Configuration

- Update the `CLIENT_ID` and `REDIRECT_URI` in `index.html` if you use your own Twitch app credentials.
