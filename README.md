# Blox Fruits Music Bot

This is a Discord bot that allows you to play music in your Discord server while you're grinding in Blox Fruits! It supports playing music from various sources (like YouTube links or search terms) directly in your voice channel.

## Features

* **Slash Commands:** Easy-to-use slash commands for all functionalities.
* **Play Music:** Play your favorite tunes while sailing the Grand Line or defeating sea beasts. Simply use the `/play` command followed by a song name or a YouTube link.
* **Queue System:** Add multiple songs to a queue and enjoy uninterrupted music sessions. Use the `/queue` command to see the current queue.
* **Pause/Resume:** Control the playback with `/pause` and `/resume` commands.
* **Skip:** Skip the current song in the queue using `/skip`.
* **Stop:** Stop the music and clear the queue with `/stop`.
etc

## Potential Issues and Troubleshooting

This bot is under development, and you might encounter some issues. Here are a few common problems and how to address them:

* **`AttributeError: 'NoneType' object has no attribute 'channel'`:** This error usually means the bot is trying to play music or send a message related to voice activity but isn't properly connected to a voice channel. Ensure you are in a voice channel when using the `/play` command. If the issue persists, try disconnecting and reconnecting the bot to the voice channel.
* **No music playing:**
    * Double-check if the bot has joined your voice channel.
    * Ensure your bot has the "Connect" and "Speak" permissions in your voice channel settings.
    * The provided link might be invalid or unavailable. Try playing a different song.
    * There might be temporary issues with the audio source.
* **Bot commands not responding:**
    * Make sure the bot is online.
    * Verify that you are using the correct slash commands (starting with `/`).
    * Check the bot's permissions in your server.

If you encounter other errors or have suggestions, please feel free to report them!

## API Key Requirement

**Important:** This bot requires an API key to fetch and play audio. To obtain the necessary API key, please join the following Discord server and follow the instructions provided there:

[**Join the API Key Server!**](https://discord.gg/3wKTDFMwvN)

Once you join the server, look for a channel (likely named `#get-api-key`, `#get-key`, or similar) where you can request or find instructions on how to get your API key. You will need to replace `"your_audio_api_key"` in the bot's code with the key you obtain.

## Setup Instructions (For Developers)

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/TestHub-off/Blox-fruit-bot-economy
    cd YOUR_BOT_DIRECTORY
    ```
2.  **Create a virtual environment (recommended):**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Linux/macOS
    .\venv\Scripts\activate  # On Windows
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Obtain your API key:** Join the Discord server mentioned above and follow the instructions to get your audio API key.
5.  **Configure the bot:** Open the bot's main Python file (e.g., `main.py`) and replace `"your_audio_api_key"` with the API key you obtained.
6.  **Get your Discord bot token:** Create a bot application on the [Discord Developer Portal](https://discord.com/developers/applications) and get its token.
7.  **Run the bot:** Replace `"YOUR_BOT_TOKEN"` in the bot's code with your actual Discord bot token and run the script:
    ```bash
    python proxy.py
    ```
8.  **Invite the bot to your server:** Use the OAuth2 URL generated on the Discord Developer Portal to invite the bot to your Discord server.

## Contributing

Contributions to this bot are welcome! If you have ideas for new features, bug fixes, or improvements, feel free to submit a pull request.

