# is-mobile
Detects whether the user is on a mobile device.

User agent sniffing for a mobile phone has gotten rather complex, so I made this component to simplify it.

# Usage
```js
var device = require('littlstar/is-mobile');

if (device.isMobile()) {
  // the person is on a mobile phone
}

if (device.isiOS()) {
  // the person is on an iOS device
}

if (device.isAndroid()) {
  // the person is on an Android device
}
```

# License
MIT
