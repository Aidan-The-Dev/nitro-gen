# Nitro-Gen
> A lightweight and easy to use package that generates **unchecked** discord nitro codes.

| ⚠️ WARNING ⚠️ |
|----------------|
| Using a nitro generator is against discord [TOS]('https://discord.com/terms') and using this package with a bot and getting your bot reported can lead to an account termination (i.e. account deletion) |

| 📜 Terms of Service |
|----------------------|

| I am not responsible for anything that happens to your account for using this package. Once you install this package using npm into your project you are at that point responsible for anything that happens and can no longer take any legal action against me.|
|-----------------|

<br><br>

# Usage

```javascript
const {NitroGen} = require('nitro-gen')
const nitro = new NitroGen()
const prefix = '!'

client.on('message', function(message) {
  if(message.content.startsWith(`${prefix}setup`)) {
    nitro.setup(message)
  }
})
```

# Classes

```javascript
.setup(message)
.gen(message)
.start(message)
```

# Support
## If you find a bug or an error you can make a new issue on our [github]('https://github.com/pog-sister/nitro-gen/blob/main/README.md')!
