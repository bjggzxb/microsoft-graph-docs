---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const languageProficiency = {
  displayName: "displayName-value",
  tag: "tag-value",
  proficiency: "proficiency-value"
};

let res = await client.api('/me/profile/languages/{id}')
	.version('beta')
	.update(languageProficiency);

```