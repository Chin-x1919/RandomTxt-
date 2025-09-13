# Anonymous Messaging with the Dumbest System Ever™

Play dumb with your friends!  
Send anonymous messages with a *totally not secure* anti-bot system (aka "press button to prove human").  
Because reCAPTCHA is too mainstream.

---

##  Features

- Anonymous messaging (nobody knows who sent it… except you)  
- "Are you human?" check (spoiler: it’s just a button)  
- Messages go straight into **Discord** via webhook  
- Only works if you have the secret link → so high security 🔐  
- 100% **Open Source Garbage™**  

---

## How to Use

1. Clone or fork this repo.  
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
   ```
   or just hit the **Fork** button on GitHub.

2. Edit `index.html` and replace:
   ```html
   const SECRET_KEY = "YOUR_SECRET_KEY";
   const DISCORD_WEBHOOK = "YOUR_DISCORD_WEBHOOK";
   ```
   with your actual secret key and Discord webhook URL.

3. Run it on literally anything that serves HTML:  
   - XAMPP  
   - Apache/Nginx  
   - GitHub Pages (yes, it even works there lol)  
   - Or just double-click `index.html` like a caveman 🪨

4. Create a link with your key:  
   ```
   http://localhost/index.html?Key=Something
   ```

5. Send the link to your friends → they type → they send → you get Discord notifications instantly.  

---

## Why not use NGL?

Because NGL looks polished.  
And me? I like my tools like I like my humor:  
**O P E N S O U R C E & S T U P I D**  
(actually i just hate third party app)

---

## Hosting Guide 

- **Localhost**: Use XAMPP or Apache → copy `index.html` → done.  
- **GitHub Pages**:  
  1. Fork repo  
  2. Go to repo → Settings → Pages  
  3. Enable Pages → pick `main` branch → `/root`  
  4. Boom, your dumb system is live on the internet.  
- **VPS/Server**: Drop it in `/var/www/html/` like a pro sysadmin who gave up.  

---

## Flowchart of the "System"

```
[User enters message] 
        ↓
[Press button to prove human] 
        ↓
[HTML form yeets message → Discord webhook] 
        ↓
[You laugh, they cry]
```

---

## License

MIT License.  
Do whatever you want with it.  
But seriously, don’t scam people using this potato system.  

---

## Contributing

1. Fork repo  
2. Make your dumb changes  
3. PR it back  
4. We’ll merge it if it’s funny enough
