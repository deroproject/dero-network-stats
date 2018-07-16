# Dero Network Status

[http://stats.atlantis.dero.live/](http://stats.atlantis.dero.live/)

## Prerequisites

* NodeJS
* NPM


### Node Side

#### Configuration

Edit stats-client.js and change : 
```javascript
const serverURL = 'https://stats.atlantis.dero.live:8080/nodes'; // You need to change IP and PORT. You need to set same port like server side
```


### Compile nodes-side 

```
npm install pkg
pkg stats-client.js
You will find 3 compiled file : Windows, Linux and MacOS. If your system is 64 bits this compiled files will be for it.
```
