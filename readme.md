<p align="center">
  <a href="https://docs.modul.tilki.dev">
    <img width="300" src="https://tilki.neocities.org/resim/tilki.png" alt="tilki">
  </a>
</p>
<center>
<p>Tilki gücünü aoi.js'den alıyor!</p>
</center>

---

<div align = "center">

**[ Doküman (Yakında) ](https://docs.modul.tilki.dev)** | **[ Destek Sunucusu ](https://tilki.dev/discord)** | **[ Website ](https://tilki.dev/)** | **[ Replit ](https://replit.com/@tilkidevelopment/tilki)** | **[ GitHub ](https://github.com/codetilki/tilki)**

</div>

---

## Bilgi

Bu modül aoi.js'de zorlananlara yaptım inşallah beğenirsiniz <3

## İndirme

```bash
### npm
npm i tilki
```

### Main

```javascript
const {AoiClient} = require("aoi.js");

const bot = new AoiClient({
token: "token",
prefix: "t!",
intents: ["MessageContent", "Guilds", "GuildMessages"],
  events: [
      "onMessage",
      "onInteractionCreate"
    ]
})



const { Tilki } = require("tilki");
const tilki = new Tilki({ bot:bot });
tilki.yeniTilki();


bot.command({
  name: "tilki-sürüm",
  code: `$tilkiV`
})
```

## Lisans
Tilki'nin lisans'ı var B) [MIT LICENSE](./LICENSE.txt).
