# Discord Rich Presence [edited for Electron]

A simple wrapper around [discord-rpc](https://npmjs.org/discord-rpc)

<b>Created</b> by <b>Gus 'devsnek' Caplan</b>. <b>Edited</b> by <b>Timothy 'Tim3Game' Beihofner</b>

### Installation
``
npm i Tim3Game/discord-rich-presence
``

### Example

```javascript
const client = require('discord-rich-presence')('180984871685062656');

client.updatePresence({
  state: 'slithering',
  details: '🐍',
  startTimestamp: Date.now(),
  endTimestamp: Date.now() + 1337,
  largeImageKey: 'snek_large',
  smallImageKey: 'snek_small',
  instance: true,
});
```
