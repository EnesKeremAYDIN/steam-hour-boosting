# Steam Hour Boosting Bot

A Node.js bot to boost play hours on specified Steam games. This tool allows users to accumulate hours on their Steam profile or in specific games by simulating playtime.

## Features

- Simulates playtime for up to **32 games simultaneously**, maximizing hour boosting efficiency.
- Easy to configure with a list of Steam App IDs.
- Works in the background, boosting hours while the bot runs.

## Installation and Setup

### Prerequisites

- **Node.js** installed on your machine.
- A **Steam account** to use for boosting hours.

### Installation

1. **Clone or Download** this repository:
   ```bash
   git clone https://github.com/EnesKeremAYDIN/steam-hour-boosting.git
   cd steam-hour-boosting
   ```

2. **Install Required Packages**:
   ```bash
   npm install
   ```

### Configuration

#### If the Account Does Not Have Steam Guard
1. **Enter Login Credentials**:
   - Open `bot.js` and enter your Steam account’s username and password on lines 6 and 7.
2. **Set Up App ID List**:
   - Specify up to 32 Steam App IDs for boosting in `bot.js` on line 13.
3. **Run Locally or Upload to a Cloud Service**:
   - You can run the bot locally or upload it to a cloud service like Heroku.

#### If the Account Has Steam Guard (Recommended)
1. **Get the Steam Guard Shared Secret**:
   - Retrieve your Steam Guard shared secret using [SDA](https://github.com/Jessecar96/SteamDesktopAuthenticator) or via a rooted [Android](https://www.google.com/search?q=how+to+get+rooted+android+steam+guard+code) or [iOS](https://www.google.com/search?q=how+to+get+rooted+android+steam+guard+code) device.
2. **Enter Login Credentials and Shared Secret**:
   - Enter your Steam username, password, and shared secret in `bot.js` on lines 6, 7, and 8.
   - Remove the double slashes (`//`) at the beginning of line 8.
3. **Set Up App ID List**:
   - Specify up to 32 Steam App IDs in `bot.js` on line 13.
4. **Run Locally or Upload to a Cloud Service**:
   - You can run the bot locally or upload it to a cloud service like Heroku.

### Cloud Service Installation (Heroku)

1. **Create and Verify a Heroku Account**:
   - Sign up at https://signup.heroku.com and verify your account at https://devcenter.heroku.com/articles/account-verification.
2. **Set Up a GitHub Repository**:
   - Create a GitHub account at https://github.com/signup.
   - Upload your bot code to your GitHub repository (see GitHub’s [quickstart guide](https://docs.github.com/en/get-started/quickstart/create-a-repo) if needed).
3. **Deploy to Heroku**:
   - Link your GitHub account to Heroku: https://devcenter.heroku.com/articles/github-integration.
   - Deploy your repository to Heroku following the [Heroku GitHub integration guide](https://devcenter.heroku.com/articles/github-integration).

### Running the Bot

After setup, you can run the bot locally or on your chosen cloud service:
```bash
node bot.js
```

## Files

- **`bot.js`**: Main script for handling hour boosting on Steam.
- **`simple_app_id_list.txt`**: Text file containing Steam game IDs to boost, supporting up to 32 games.
- **`package.json`**: Lists dependencies and configuration details for the Node.js project.

## Warnings

- While no penalties have been reported for using this method, using it is at your own risk, and Steam or Valve could implement measures against such activities.
- When entering App IDs, ensure there is a comma after each ID except the last one.
- Make your GitHub repository private to secure your credentials.

*Note:* An upcoming update will enable bot management via Discord for more streamlined control.

## Disclaimer

This tool is intended for personal use. Ensure compliance with Steam’s terms of service, as unauthorized use may lead to account suspension.
