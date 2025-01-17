---
sidebar_label: Slack Provider
---

# Slack

:::note Brief Description
Slack provider is a provider that allows to send notifications to Slack
:::

## Inputs
The `notify` function take following parameters as inputs:
- `message`: Required. Message text to send to Slack
- `blocks`: Optional. Array of interactive components like inputs, buttons


## Outputs


## Authentication Parameters
The webhook_url associated with the channel requires to trigger the message to the respective channel.

## Connecting with the Provider
1. Create a Slack app (if you don't have one already)
2. Enable Incoming Webhooks
3. Create an Incoming Webhook
4. Use your Incoming Webhook URL to post a message

## Notes


## Useful Links
- https://api.slack.com/messaging/webhooks
