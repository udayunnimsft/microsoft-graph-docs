
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const list = {
  name: "Books",
  columns: [
    {
      name: "Author",
      text: { }
    },
    {
      name: "PageCount",
      number: { }
    }
  ],
  list: {
    template: "genericList"
  }
};

let res = await client.api('/sites/{site-id}/lists')
	.version('beta')
	.post({list : list});

```