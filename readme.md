# DOSI
DOSI Auto Claim DON & Join Adventure

## Installation
- Clone this repository
```bash
# clone this repository
git clone https://github.com/xrizkiiaprmn/dosi
# after complete
cd dosi
```
- Install library
```bash
# use
yarn

# or
npm i
```

## Usage
- Fill dosi session account in file sessions.txt, in session property
- For multiple account, separate them with enter
- Run
```bash
# use
yarn start

# or
npm run start
```
- Done, auto claim every 24 Hours
- Please give me stars 

## Update Feature (Send Log to Webhook Discord)
- Send Update Account Information (Balance and Adventure Count) in Discord using webhook
- Interest to use it? Just set value for variable enableWebhook in line 9 with true
- Next step, you must configure your webhook to receive update information account with edit value in line 3 configurationWebhook.js with your webhook url. And run it
- If success, you can find in your channel discord the message of webhook (bot). And copy message ID
- After that, you must fill your webhook url and message ID in configuration.json
- Just run it and see update in your channel