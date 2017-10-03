## Setup
`yarn add fetch-once-q`

or

`npm install --save fetch-once-q`

## Use

```javascript
import { json as fetchJSON } from 'fetch-once-q';

fetchJSON('http://api.mysite.com/products/1').then(r=>console.log(r));
fetchJSON('http://api.mysite.com/products/1').then(r=>console.log(r));

// Check the Network tab in the dev tools.
```
