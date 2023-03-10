## WebdriverIO with Appium

Content:
1. Requirements
2. Start project
3. Available scripts

### Requirements

Nodejs 16.x^

### Start project

For start you need to follow next step:

1. Download or fork this repo
2. Run `npm install`
3. Change the "deviceName", "platformName", "platformVersion" in `config/wdio.conf.local.js` for you device
4. Run `wdio.local`

### Available scripts

For run on browserstack:

On Samsung Galaxy A51 - `npm run wdio:bs:galaxy:a51`
On Samsung Galaxy S21 Ultra - `wdio:bs:galaxy:s21u`
On each device - `wdio:bs:all:devices`

For run locally:

`npm run wdio:local`