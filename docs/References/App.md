## App
App module contains necessary APIs for current NW.js application.

### App.getProxyForURL
* url `{String}` URL of the string
* Return `{String}` Proxy information for the URL.

The proxy information is a string like `"DIRECT"` or `"HTTP www.myproxy.com:8080"`

For example,
```javascript
var proxy = nw.App.getProxyForURL('https://www.github.com/');
console.log(proxy);
```

### App.dataPath
* Return `{String}` Local data path for cache and indexes
