# PixelDrain RateLimit Bypasser 🚀

![Project Preview](/screenshot.png)

## 🤔 The Problem

PixelDrain limits you to 6GB downloads per day. Seriously? In 2026?

## 🎉 The Solution

A simple tool that:
- Bypasses the 6GB/day download restriction
- Gives you lightning-fast downloads
- Works across multiple servers

## 🛠 How It Works

1. Paste your PixelDrain URL
2. Click "Convert"
3. Get a bypassed link
4. Download without limits

## 🔧 Technical Magic

The core of the magic happens in this snippet:

```javascript
// List of available workers
const workers = [
  "pd1.sriflix.online",
  "pd2.sriflix.online", 
  "pd3.sriflix.online",
  "pd4.sriflix.online",
  "pd5.sriflix.online"
];

// Pick a random worker
const randomWorker = workers[Math.floor(Math.random() * workers.length)];

// Construct redirect URL
const redirectUrl = `https://${randomWorker}/api/file/${fileId}?download`;
```

Key features:
- Randomly selects from multiple proxy servers
- Dynamically generates download links
- Bypasses original rate limitations

## 🎓 Educational Purpose

**Disclaimer:** This project is a technical exploration of web technologies, proxy mechanisms, and request routing. It's designed to demonstrate:
- Cloudflare Worker capabilities
- Dynamic server selection
- URL manipulation techniques

🚨 **Not Intended for Circumventing Service Terms**

## 🚧 Roadmap

- [X] Backend API Development
- [X] Enhanced Error Handling
- [ ] User Authentication (Maybe)
- [ ] Detailed Logging

**Coming Soon:** A more robust, feature-rich version that might just change the download game! 

## 🚨 Quick Notes

- Use responsibly
- Not affiliated with PixelDrain
- For educational purposes

## 📜 License

MIT License

---

**Pro Tip:** If downloading files was an Olympic sport, this would be your gold medal 🏅

Remember, some heroes don't wear capes. Some just write clever JavaScript that laughs in the face of download limits. 

**Made in Ceylon with ❤️ by sh13y** - Where innovation meets determination 🇱🇰

Stay fast, stay curious! 🚀💻
