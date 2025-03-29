** 🎀 Vanity-Role-Bot **

This is a Discord bot that automatically assigns and removes roles to members based on their custom status. When a member sets a specific keyword in their status (defined in the bot's configuration), the bot assigns them a role, and when they remove it, the bot removes the role.

📌 Features:

Assigns a specific role to members based on their custom activity status.

Removes the role if the member's status no longer matches the defined keyword.

Sends log messages in a specific channel with embed notifications about role changes.


📋 Requirements:

Python 3.6+

discord.py library


⚙️ Setup Instructions:

1. Install Python and Dependencies:

Make sure Python 3.6 or above is installed. If not, you can download and install it from python web.

Install the necessary Python package using pip:

pip install discord.py

2. Configure the Bot:

1. Create a new bot on the Discord Developer Portal.


2. Copy the bot token and paste it into the config.json file.


3. Define the role and keyword in config.json:




{
  "TOKEN": "YOUR_BOT_TOKEN",
  "GUILD_ID": "YOUR_SERVER_ID",
  "SUPPORTER_ROLE_ID": "YOUR_ROLE_ID",
  "LOG_CHANNEL_ID": "YOUR_LOG_CHANNEL_ID",
  "KEYWORDS": ["custom_status1", "custom_status2", "custom_status3", "custom_status4"]
}


3. Run the Bot:

Start the bot by running:

python main.py

4. Invite the Bot:

Use the OAuth2 link to invite the bot to your server with Manage Roles and Read Member Status permissions.

Enjoy your Vanity-Role-Bot!


🔗 Need help , add me on discord [heisen.48]
