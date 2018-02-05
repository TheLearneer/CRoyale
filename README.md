# CRoyale

Croyale is a powerful node.js module that allows you to interact with the [cr-api](http://cr-api.com/) very easily.

- Object-oriented
- user friendly
- maximum coverage of the API

## Installation
**Node.js 8.0.0 or newer is required**

Installing: `npm install croyale`

## Example usage
```js
const CRoyale = require('croyale');
const client = new CRoyale.Client('token');

client.getPlayer('CVLQ2GV8', { keys: ['name'] })
	.then(player => {
		console.log(`The player's name is ${player.name}`);
	});

```
## Credits
- The major credit for the existence of this wrapper goes to the developers of the api; SML and Selfish.
- In the mean time I would like to thank every individual people who have directly or indirectly helped me.

## Links
* [Documentation](https://thelearneer.github.io/croyale/)
* [CRoyale Discord server](https://discord.gg/6KvdGB3)
* [cr-api Discord server](http://discord.me/cr_api)
* [GitHub](https://github.com/TheLearneer/croyale)
* [NPM](https://www.npmjs.com/package/croyale)

## Contributing
Before creating an issue, please ensure that it hasn't already been reported/suggested, and double-check the
[documentation](https://thelearneer.github.io/croyale/).  
Make sure the changes you made aren't breaking things and are working fine if you'd like to submit a PR.

## Help
If you don't understand something in the documentation, you are experiencing problems, or you just need a gentle
nudge in the right direction, please don't hesitate to join our official [Croyale Server](https://discord.gg/6KvdGB3).
