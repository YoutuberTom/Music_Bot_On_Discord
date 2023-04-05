Have you ever wanted to host a music discord bot? If yes then this project is for you. You can easily host your own music discord bot with many features in just 3 steps.

# **Dependencies:**

## Python version:

    Python >= 3.8.0

## Python libraries:

| Library |  Version  |
|:--------|:----------|
|discord  |>= 2.2.2   |
|pynacl   |>= 1.5.0   |
|yt_dlp   |>= 2023.3.4|
|asyncio  |>= 3.4.3   |


# **License:**

This project is distributed under [MIT license](https://github.com/YoutuberTom/Music_Bot_On_Discord/blob/main/LICENSE).

# **Help:**

## Step 1: Create a bot.

- You can [click here](https://discord.com/developers/applications) to create a new bot.
- You'll need to change the bot's scopes and permissions for it to work.
- Finally, create a new token then save it in a safe place as you will only see it once.

## Step 2: Install requirements.

- You can [click here](https://ffmpeg.org/download.html) to download ffmpeg.
- You also need to install other required libraries listed in [requirements.txt](https://github.com/YoutuberTom/Music_Bot_On_Discord/blob/main/Music_Bot/requirements.txt).

## Step 3: Modify config.

- Open the [config.ini](https://github.com/YoutuberTom/Music_Bot_On_Discord/blob/main/Music_Bot/config.ini) and change the config data.
- Replace **"ffmpeg"**  with the path to ffmpeg (optional).
- Replace **"\<Bot's token>"** with the bot's token that you've saved.

And you just finished creating your music discord bot. Now you can start using your self-hosted bot by running [this](https://github.com/YoutuberTom/Music_Bot_On_Discord/blob/main/Music_Bot/Music_Bot.py).
