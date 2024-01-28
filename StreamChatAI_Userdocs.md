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
    - [2.3.3 Session Settings](#2.3.3-session-settings)
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

- [4. FAQ](#4-faq)
- [5. Troubleshooting](#5-troubleshooting)
  - [5.1 Manual Start](#5.1-manual-start)
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

> [!IMPORTANT]
> StreamChatAI will never use your credentials or Twitch-Authentication for purposes other than to provide our service. We will not make any changes other than what the bot's functionality provide **AND** you have set up.

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
Clicking this will open a new window where you can assign a new user to a role. In the `Search` field, type your bot's name. For convenience purposes, we've used `StreamChatAI`, but obviously you would search for your own bot's name here.
![Imgur Twitch Add Role](https://i.imgur.com/QQT3YHW.png).

For the best experience, you would set your bot's permissions to `Editor`. This will grant access to all current and future interaction types. If you don't feel comfortable, you can set it to `Moderator` instead. This will still allow for most of the features. Do be aware though, that some features displayed on the [dashboard](#dashboard) will not be able to run properly.

> !

Having set the bot's roles, you are done with the permissions and you can close the window.
For in-depth information on what roles and permissions are available, pleare refer to [Twitch Help: Roles](https://help.twitch.tv/s/article/Managing-Roles-for-your-Channel?language=en_US).

---

### 2.3 Settings

Now that the bot is set up, -perhaps even renamed- and connected to your channel, it's time to configure it's behavior. Let's hop onto our [`dashboard`](#dashboard) and scroll to the bottom of the page where we will see 4 icons. ![Imgur](https://i.imgur.com/Q705tA7.png)
These icons -from left to right- are [`FAQ`](#4.1-FAQ), [`Settings`](#4.2-Settings), [`Account`](#4.3-Account), and [`Session Settings`](#2.3.3-session-settings).

#### 2.3.1 User Settings

To get to the settings, click on the `Settings` button, represented by a gear icon.
In there, you will be greeted by a slew of options in 2 categories, `User Settings` and `Bot Settings`. There are 3 available settings that configure the User's interaction with the bot and `StreamChatAI`'s community and website.
The available settings are:

- `Feature on the homepage`. (toggle on/off)
  Enabeling this setting will allow us to display your channel on our homepage. It will include your channel name, your bot's name and a link to your channel. This is a great way to get some exposure and grow your community. If you do not wish to be displayed on our homepage, you can Keep this setting disabled.

- `Announce on Discord`. (toggle on/off)
  When this setting is enabled, we will announce it on our dedicated Discord channel whenever you go live. This is another great way to get some exposure and grow your community. If you do not wish to be announced on our Discord, you can keep this setting disabled.

- `Disable Beta Functionality` (toggle on/off) **_BETA ONLY_**
  When enlisted in the Beta testing program, you will have access to some of our newest features. This setting is enabled by default, synchronous to your Beta program enrollment. To circumvent issues posed by the Beta features, you can disable this setting and revert to regular functionality. To enable this setting again, you will need to reach out to to do so.

#### 2.3.2 Bot Settings

Following up on the `User Settings`, we have reached the `Bot Settings`. This is your bot's core behavior and shapes the interactions with your community. These settings tend to **change regularly** over time, so come back here to find out what the newest features are.

- `Boot on Stream Startup` (toggle on/off)
  To manage resources, the bot cannot be running 24/7. Luckily, Twitch provides us with a nice hook to start the bot whenever you go live and having this setting enabled will automatically start your bot whenever you do so. Your bot might take a couple of minutes to start up, so provide a little grace period before you start interacting with it. If you have `Welcome message` enabled in the [Contexts](#3.10-contexts), your bot will send that message to your chat as soon as it's done starting up. It is **highly recommended** to keep this setting enabled. If you do not want your bot to start automatically, you can keep this setting disabled.

  > [!WARNING] If you disable this function, you will have to [Manual Start](#5.1-manual-start) our bot whenever you want to. When our API cannot pick up on your channel being live, it will automatically shut down after `5 minutes`.

- `Enable replies` (toggle on/off)
  With replies enabled, your bot will be able to respond to messages in chat. These can be [Commands](#3.02-commands), [Nicknames](#3.2.2-bot-settings) or random messages in your chat.
  This is a core feature of our bot, so it's **highly recommended** to keep this setting enabled. If you do not want your bot to respond to messages in chat, you can keep this setting disabled.
  > [!WARNING] Disabling this setting will block all chat interactions. This means that [Commands](#3.02-commands), [Nicknames](#3.2.2-bot-settings) and any other chat messages will be ignored. Other features like [Reactions](#3.03-reactions), [Rewards](#3.04-rewards), [Recurring Messages](#3.05-recurring-messages) and [Multimedia](#3.06-multimedia) will still work, as long as they do not require chat input.
