
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const directoryObject = {
  directoryObject: {
  }
};

let res = await client.api('/directoryRoles/{id}/members/$ref')
	.version('beta')
	.post({directoryObject : directoryObject});

```