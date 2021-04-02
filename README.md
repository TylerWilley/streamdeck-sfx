# Streamdeck SFX Plugin

## Overview

Connects to a SignalFX account using an Access Token

Polls the API once per minute to get global alert counts on that account.

If there are any critical alerts, the button will be RED and display the number of critical alerts.

Otherwise, if there are any major alerts, the button will be ORANGE and display the number of major alerts.

Etc.

Pressing the button will open the alerts page for the SignalFX Organization it is connected to.

## Setup

- Organization ID
- Access Token

Enter your Organization ID into the Organization ID field

Create a SignalFX [Access Token](https://docs.signalfx.com/en/latest/admin-guide/tokens.html#access-tokens)

Enter this token into the Access Token field

## Other Information

The plugin will poll the SignalFX API once per minute while active. It will not poll while inactive. This is the same polling rate the web application uses when you have the alerts page open in the browser.