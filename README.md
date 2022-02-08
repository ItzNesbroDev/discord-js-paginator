<h1 align="center">Welcome to discord-js-paginator 👋</h1>
<p>
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/ItzNesbro" target="_blank">
    <img alt="Twitter: ItzNesbro" src="https://img.shields.io/twitter/follow/ItzNesbro.svg?style=social" />
  </a>
</p>

## Install

```sh
npm i @itznesbrodeveloper/discord-js-paginator
# or
yarn add @itznesbrodeveloper/discord-js-paginator
```

## Useage
```js
const paginator = require("@itznesbrodeveloper/discord-js-paginator");

const { MessageEmbed } = require("discord.js");

const embed1 = new MessageEmbed();
.setTitle("Page 1")
const embed2 = new MessageEmbed();
.setTitle("Page 2")

// Make An Array For Embeds
let pages = [
    embed1,
    embed2,
    // More Embeds Here
]

paginator(msg, pages, emojiList, timeout)
// EmojiList Default Value: ⏪ ⏩
```

## Author

👤 **ItzNesbro**

* Website: itznesbro.netlify.app
* Twitter: [@ItzNesbro](https://twitter.com/ItzNesbro)
* Github: [@ItzNesbroDev](https://github.com/ItzNesbroDev)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/ItzNesbroDev/discord-js-paginator/issues). 

## Show your support

Give a ⭐️ if this project helped you!

