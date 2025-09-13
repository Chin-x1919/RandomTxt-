# Anonymous Q&A but Opensource

![MIT License](https://img.shields.io/badge/license-MIT-green) 
![Open Source Garbage](https://img.shields.io/badge/open--source-garbage-red)
 
Send anonymous messages with a *totally not secure* anti-bot system (aka "press button to prove human").  
Because reCAPTCHA is too mainstream.

---

##  Features

- Anonymous messaging (nobody knows who sent it… yep noone if you don't believe me go read source code)  
- "Are you human?" check (spoiler: it’s just a button)  
- Messages go straight into **Discord** via webhook  
- Only works if you have the secret link → so high security 🔐
- 100% **Open Source Garbage™**  

---

## Demo

### What users should see
*(aka the "wow such secure" landing screen)*  
<img width="2880" height="1620" alt="main screen" src="https://github.com/user-attachments/assets/59d15798-c0b1-4312-b5aa-1db91e53a3e1" />

---

### Message sent! popup
*(yes, it actually goes to Discord — unbelievable, I know)*  
<img width="2880" height="1620" alt="popup success" src="https://github.com/user-attachments/assets/9bcef80a-4ce8-4bc5-a692-531d5cc7a314" />

---

### Without secret key
*(what freeloaders will see — literally nothing)*  
<img width="2880" height="1626" alt="no key" src="https://github.com/user-attachments/assets/00da7b14-4356-4858-b746-2896a22ed3b7" />

---

### Discord message
*(the moment of truth — your friend's roast/confession lands here)*  
<img width="1592" height="224" alt="discord message" src="https://github.com/user-attachments/assets/89a84cc8-c648-468d-a0ce-ffe795d2d0b9" />

---

## How to Use

1. Clone or fork this repo.  
   ```bash
   git clone https://github.com/Chin-x1919/anonymous_q-a.git
   ```
   or just hit the **Fork** button on GitHub.

2. Edit `index.html` and replace:
   ```html
   const SECRET_KEY = "YOUR_SECRET_KEY"; //(Line191)
   const DISCORD_WEBHOOK = "YOUR_DISCORD_WEBHOOK";// (Line192)
   ```
   with your actual secret key and Discord webhook URL.
   (Line numbers may change if I mess with the code later, so ctrl+F it if needed.)


4. Run it on literally anything that serves HTML:  
   - XAMPP  
   - Apache/Nginx  
   - GitHub Pages (yes, it even works there lol)  
   - Or just double-click `index.html` like a caveman 🪨

5. Create a link with your key:  
   ```
   http://localhost/index.html?Key=Something
   ```

6. Send the link to your friends → they type → they send → you get Discord notifications instantly.  

---

## Why not use NGL?

Because NGL looks polished.  
And me? I like my tools like I like my humor:  
**O P E N S O U R C E & S T U P I D**  
(actually i just hate third party app)

##NGL vs This Potato Project

### NGL (corporate edition)
- Download the app (big as a dumpster)  
- Sign up, log in, done in 1 min  
- Polished UI, scale = millions  

<img width="2188" height="1144" alt="image" src="https://github.com/user-attachments/assets/72a61a45-047f-4f02-b4d3-4ef5c0d375ab" />


---

### This project (budget < 20 THB)
- Fork this repo  
- Edit the code (yes, manually)  
- Push to GitHub Pages  
- Pray it builds  
- Finally… it works 🎉  

So yeah… **it’s actually harder to use than NGL.**  
But hey, at least it’s **O P E N S O U R C E** ✨  

<img width="2048" height="1153" alt="image" src="https://github.com/user-attachments/assets/7219d6fb-02b0-48d1-8649-99eebb24d9bc" />

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
