# Serverless Telegram Blur Sticker Delete Bot
an Telegram Bot using the Serverless Framework ⚡🤖

## Usage

### What do I need?
- A AWS key configured locally, see [here](https://serverless.com/framework/docs/providers/aws/guide/credentials/).
- NodeJS. I tested with v8.9.0.
- A Telegram account.

### Installing
```
# Install the Serverless Framework
$ npm install serverless -g

# Install the necessary plugins
$ npm install

# Get a bot from Telegram, sending this message to @BotFather
$ /newbot

# Put the token received into a file called serverless.dev.yml, like this
$ cat serverless.dec.yml
TELEGRAM_TOKEN: <your_token>

# Deploy it!
$ serverless deploy

# With the URL returned in the output, configure the Webhook
$ curl https://<your_url>.amazonaws.com/dev/hook
```

Now, just start a conversation with the bot :)
