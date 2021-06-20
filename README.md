# BrawlBio.js

An Official NPM Library For [BrawlBio](https://bs.is-a.dev) That Allows You To Interact With [BrawlBio API](https://bs.is-a.dev/api) Easily. 

## Install

`npm i brawlbio.js`

## Usage

```js
const brawlbio = require('brawlbio.js')

brawlbio('TOKEN')
brawlbio.search('Type', 'Slug/Tag').then((data) => { 
// some action  
})
```

- ### Example
```js
brawlbio('VkRCVERrVZOVVZVVhhW...')
brawlbio.search('user', 'joe').then((data) => { 
  // output data
  console.log(data)
  
})
 
// Output Data Should Be
{
  type: 'get-user',
  tag: '82PGQVJ2L',
  slug: 'joe',
  user: 'Joe Lee | イサム(469091175517782018)'
}

// Output Data ( without token )
{
  type: 'get-user',
  tag: '82PGQVJ2L',
  slug: 'joe'
}
```
  - ### Types

| GetBy-User : `user`  | GetBy-Tag : `tag` |
| ------------- | --------- |

  - ### Token 
  [BrawlBio](https://bs.is-a.dev) require users to request its API with an `api-token` in order to get complete response data from BrawlBio. Click Here To [Learn More](https://bs.is-a.dev/docs) About Getting A Token.

  ```js
  brawlbio('YOUR_TOKEN')
  ```

## Support
Join Our Official [BrawlBio Community](https://discord.gg/Ca4yEvTsXB) Server To Get Help.

## Credits 

```
Owner : @joeleeofficial <tojoeleeofficial@gmail.com>
This project is licensed under the terms of Apache 2.0 License
```

