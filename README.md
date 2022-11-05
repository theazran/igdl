# igdl

Simple Scrapper for Instagram Downloader

Only available for download single post, reels.
If multiple posts, only the main one is downloaded.

```bash
npm install igdl
```

# Usages:

```javascript
const igdl = require("igsimpledl");
igdl("https://www.instagram.com/p/CXCnrUFhsZS/").then((data) => {
  console.log(data);
});
```

# Result:

```json
{
  "result": {
    "ownAPI": "@theazran_",
    "url": "https://tinyurl.com/2fndqq8v"
  }
}
```

### Contact Me:

> - Facebook: [M ASRAN](https://www.facebook.com/theazran)

> - Instagram: [M ASRAN](https://instagram.com/theazran_)
