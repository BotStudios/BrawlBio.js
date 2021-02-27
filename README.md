# BrawlBio.js

Welcome To BrawlBio.js, An Official NPM Package For [BrawlBio](https://bs.is-a.dev). With This NPM Package, You Can Interact With Its API Easily.

## Install

`npm i brawlbio.js`

## Usage

```
const brawlbio = require('brawlbio.js')

brawlbio.search('Type', 'Slug/Tag').then((data) => { 
// some action  
})
```

- ### Example
```
brawlbio.search('user', 'joe').then((data) => { 
  // output data
  console.log(data)
  
})
 
// Output Data Should Be
{
  type: 'get-user',
  tag: '82PGQVJ2L',
  user: 'Joe Lee | イサム(469091175517782018)'
}
```
  - ### Types

  | Types  | 
| ------------- | ------------- |
| GetBy-User : `user`  | GetBy-Tag : `tag` 


## Credits 

```
This Project Is Owned & Managed By @joeleeofficial <tojoeleeofficial@gmail.com>
And Under Apache 2.0 License
```


