# StreamChatAI ![Skye](https://imgur.com/Z8vyJC6.png)

Documentation and instructions for StreamChatAI users, powered by the Beta-testing team :test_tube:.

### Table of Contents

- [1. Introduction](#1-introduction)
- [2. Getting Started](#2-getting-started)
  - [2.1 Registering](#2.1-registering)
    - [2.1.1 Custom Bot Name](#2.2.1-custom-bot-name)
  - [2.2 Bot Permissions](#2.2.2-bot-permissions)
  - [2.3 Settings](#2.3-settings)
    - [2.3.1 User Settings](#2.3.1-user-settings)
    - [2.3.2 Bot Settings](#2.3.2-bot-settings)
- [3. Features](#3-features)

  - [3.01 Dashboard](#3.01-dashboard)
  - [3.02 Commands](#3.02-commands)
  - [3.03 Reactions](#3.03-reactions)
  - [3.04 Rewards](#3.04-rewards)
  - [3.05 Recurring Messages](#3.05-recurring-messages)
  - [3.06 Multimedia](#3.06-multimedia)
  - [3.07 TTS - Text-to-speech **_BETA ONLY_**](#3.07-tts---text-to-speech)
  - [3.08 Memory **_BETA ONLY_**](#3.08-memory)
  - [3.09 Variables](#3.09-variables)
  - [3.10 Contexts](#3.10-contexts)
  - [3.11 Browser Sources](#3.11-browser-sources)

  ***

## 1 Introduction

The industry leading twitch AI chatbot. Able to liven up any streams with random interactions, in-depth discussions, commands, and more. Integrates seamlessly with TwitchAPI which allows for a wide range of features and customizability. Every streamer is unique and StreamChatAI is here to help you stand out from the crowd.

This bot is currently public and free to use, but it is in `ACTIVE` development. This means some functionality may be limited, broken, or missing.

For more information, please visit our [website](https://streamchatai.com/) or join our [discord](https://discord.gg/yXgqDjuuBY).

---

## 2 Getting Started

### 2.1 Registering

To be able to make use of our service, we will need our bot to have some permissions on your channel. These permissions are granted by logging in with your Twitch account.

To do this, go to our [website](https://streamchatai.com/) and click on the `Login / Register via Twitch` button. This will redirect you to Twitch where you will be asked to authorize our bot to join your channel. ![Imgur](https://imgur.com/Xj5Kst2.png)

Once you have authorized with Twitch, you will be forwarded back to our website, which now displays your bot's [dashboard](#dashboard). _*you're all set!*_ ... almost.

### 2.2.1 Custom Bot Name

We strive to provide a unique experience for all of our users. To help achieve this, we allow you to customize your bot's name. This, however, is a feature exclusively available for users on our `Emerald` or `Ruby` plans. If you are on our `Sapphire` plan, you will need to upgrade to one of the other plans to be able to customize your bot's name.

Changing your bot's name is a little tricky, but we're here to guide you through. Bots on Twitch are not just a username, but also an account. `MyAiBot` is our default bot's name, which is bound to our account. To have a custom name, you will need an additional Twitch account and transfer the bot there. This can either be a new account, or an existing one. If you already have a bot account and wish to use that, be aware that interactions might be conflicting and might result in unwanted behavior. To mitigate this, make sure you have no overlapping functionality or your account is only registered with 1 bot. If you are unsure, we recommend creating a new account.

To create a new account, go to [Twitch](https://twitch.tv) and click on `Sign Up`. Fill in the required information and click on `Sign Up`. You will be asked to verify your email address. You are able to registered a new account on your already registered email address. Once you have verified your email address with the new account, you are ready to transfer your bot.

To transfer your bot, go to your [dashboard](#dashboard) and click on `Account`. Here you will find the button `Change Bot Name`. Clicking this will start the migration process. Follow the prompts and you will be able to transfer your bot to your new account. Once the transfer is complete, your bot will no longer be called `MyAiBot`, but instead will be called what your new account is called. Congratulations, you have successfully changed your bot's name! :tada:

---

### 2.2.2 Bot Permissions

To make the best use of our bot, we need to give it some permissions. These permissions are granted through your Twitch account roles management.
Log in to your Twitch and go to your [Creator Dashboard](https://dashboard.twitch.tv). In the left hand column, click on `Community` and then on `Roles Manager`. Here you will see a list of all users that have a custom role on your channel. ![Imgur Twitch creator dashboard menu](https://imgur.com/gGIscGF.png)
On the top-right of the table, you will find the `Add New` button.
![Imgur Twitch creator dashboard roles Add New](https://imgur.com/fx56J5Y.png)
