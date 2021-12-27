# ram-api.js

a npm module to connect to ram api easier

## Install

install axios `npm i axios` or `yarn add axios`
install the logs `npm i winston-console-format winston ` or `yarn add winston-console-format winston `

`npm i ram-api.js` or `yarn add ram-api.js`

This package was more for a test but I may make a new package for each bot.

### Example

```javascript
const ramapi = require("ram-api");
const apiv = "v3"; //v2 and up are available ram api versions note versions

ramapi.apiversion(apiv); // outputs rather the api is outdated or not

ramapi.apihug(apiv).then(async (data) => {
	console.log(await data.data.url);
});
```

## Missing endpoints

ram api endpoints can be found at https://ram.gamearoo.top/api/docs

In the event that the ram api is on v4 instead of v3 you can always use axios to connect to it manually

## Custom connections

We currently have no way to make a connection Manually however we are working on a way in the event the ram api updates b4 we update this package

## Support

email : support@gamearoodev.com
discord: https://discord.gamearoodev.com
