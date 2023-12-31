# Minecraft Server Showcase Bot

[![GitHub issues](https://img.shields.io/github/issues/g9militantsYT/Minecraft-Server-Showcase)](https://github.com/g9militantsYT/Minecraft-Server-Showcase/issues)
[![GitHub stars](https://img.shields.io/github/stars/g9militantsYT/Minecraft-Server-Showcase)](https://github.com/g9militantsYT/Minecraft-Server-Showcase/stargazers)

The Minecraft Server Showcase Bot is a Discord bot that allows users to showcase Minecraft servers and retrieve information about them.

## Features

- Query Minecraft servers and display information with MOTD (Message of the Day).
- Handle user input for specifying domains and ports.
- Automatic error logging and reporting.

## Installation

To install the bot, follow these steps:

1. Clone the repository:

    ```
    git clone https://github.com/g9militantsYT/Minecraft-Server-Showcase.git
    cd Minecraft-Server-Showcase
    ```

2. Install dependencies:

    ```
    npm install
    ```

3. Set up environment variables:

    Create a .env file and add the following:

    ```
        BOT_TOKEN=
        GUILD_ID=
        CLIENT_ID=
        CHANNEL_ID=
        MANAGER_ROLE_IDS=
        WEBHOOK_URL=
        SHOWCASE_WEBHOOK_URL=
    ```
    You can have as many manager roles as you want, separate their role ids with commas
Enter the appropriate values

4. Run the bot:

    ```
    node .
    ```

5. Usage

    /addserver
    Add or update server information
    /help
    Get information about available commands
    /info
    Get information about the bot and its author
    /removecooldown
    Remove cooldown for a user
    /showcase
    Showcase Minecraft server information
    /userinfo
    Fetch server information
    /whitelistedips
    Show whitelisted IPs

6. Support and Feedback

    If you encounter any issues or have suggestions, feel free to open an issue.

## Additional Links

- [Website](https://g9aerospace.in/)
- [YouTube](https://www.youtube.com/@G9AEROSPACEYT)
