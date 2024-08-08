# RatterScanner Site

A website made for RatterScanner that let the users see more details about a scan, from a file or a scan ID.

You can test the website directly from [here](https://scan.ratterscanner.com/).

## Running

- Rename the config-example.json file to config.json and add your API key to "apiKey": "<apikeyGoHere>",
- Add the recaptcha site key and secret key to  "captchaKey": "<captchaKeyGoHere>" and "siteKey": "<siteKeygoHere>"
- Make any other config changes 
- Run `npm install` to download libraries
- Run `npx tsc` to compile the typescript into js
- Run `npm run start` to start the webserver.

# Config
All configuration is done in the config.json file.
