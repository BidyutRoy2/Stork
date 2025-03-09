# Stork Auto Bot

![image](https://github.com/user-attachments/assets/8c909339-0130-4170-b923-b4df4d0c7693)

Automated validation bot for the Stork Oracle network. This bot helps you automate the verification process to earn rewards through the Stork Oracle system.

## Features

- Automatically fetches signed price data from Stork Oracle API
- Validates price data according to predefined rules
- Submits validation results back to the API
- Handles token refresh for continuous operation
- Displays validation statistics and user information
- Configurable validation interval
- Support for proxy servers to distribute requests
- Multi-threaded processing for improved performance

## Requirements

- Node.js 14.0.0 or higher
- Valid Stork Oracle account

1. Register Link [HERE](https://t.me/hiddengemnews/12318)

## Installation bot

2. Clone the repository:
```
git clone https://github.com/BidyutRoy2/Stork.git
```

3. Navigate to the project directory:
```
cd Stork
```

4. Install dependencies:
```
npm install
```

5. Set Your Stork Account Email & Password
```
nano accounts.js
```
### To Save File (CTRL + X + Y Then Hit ENTER)

6. ### Start the bot
```
npm start
```

8. ## If an error occurs after a long time, Stop (CTRL+C)  (npm install)  (npm start)

The bot will:
1. Authenticate using your credentials from config.json
2. Fetch signed price data at regular intervals
3. Validate each data point
4. Submit validation results to Stork Oracle
5. Display your current statistics

## Troubleshooting

- If you see authentication errors, check that your username and password in config.json are correct
- If the bot fails to start, ensure your config.json file is properly formatted JSON
- If you see token-related errors after successful authentication, the tokens.json file may be corrupted - delete it and let the bot regenerate it
- For connection issues, check your internet connection and verify the Stork Oracle API is accessible
- If using proxies, check that your proxies.txt is properly formatted and proxies are operational

## Disclaimer

This bot is provided for educational purposes only. Use at your own risk. The authors are not responsible for any consequences that may arise from using this bot, including but not limited to account termination or loss of rewards.
