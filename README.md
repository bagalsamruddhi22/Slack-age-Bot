# Slack-age-Bot
This Go application is a Slack bot that calculates a user's age based on their birthdate. The bot interacts with Slack users to receive their birthdate and responds with their age.

Features

- **Calculate Age**: The bot calculates the age based on the provided birthdate.
- **Slack Integration**: Responds to messages in Slack and provides age calculations.
- **Simple Interaction**: Easy-to-use interaction with Slack users.


## Installation

To set up the Slack Age Bot locally, follow these steps:

1. **Clone the repository**

   ```bash
   git clone https://github.com/bagalsamruddhi22/Slack-age-Bot.git
   
2. **Navigate to the project directory**
   cd slack-age-bot

3. **Install dependencies**
   go mod tidy

4.**Configure Slack App**

Create a new Slack app via the Slack API.
Enable the necessary permissions (e.g., chat:write, commands).
Obtain the OAuth token and set it in your environment variables.

5.**Set Up Environment Variables**
Create a .env file or set environment variables with the following information:
SLACK_BOT_TOKEN=your-slack-bot-token
Replace your-slack-bot-token with the token you obtained from Slack.

**Usage**
To run the bot, use the following command:
**go run main.go**
The bot will start and listen for commands in Slack. Users can interact with the bot by sending their birthdate, and the bot will respond with their calculated age.

## Example 
User sends a message to the bot: My birthdate is 1990-01-01.
The bot responds: You are 34 years old
