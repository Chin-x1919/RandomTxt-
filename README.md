# Anonymous Messaging with the Dumbest System Ever™

Play dumb with your friends!  
Send anonymous messages with a *totally not secure* anti-bot system (aka "press button to prove human").  
Because reCAPTCHA is too mainstream.

---

## Features

- Anonymous messaging (nobody knows who sent it… except you)  
- "Are you human?" check (spoiler: it’s just a button)  
- Messages go straight into **Discord** via webhook  
- Only works if you have the secret link → so high security 🔐  
- 100% **Open Source Garbage™**  

---

## 🚀 How to Use

1. just hit the Fork button on GitHub
2. Edit index.html and replace:
const SECRET_KEY = "YOUR_SECRET_KEY"; (Line121)
const DISCORD_WEBHOOK = "YOUR_DISCORD_WEBHOOK"; (Line167)
with your actual secret key and Discord webhook URL.
3.Run it on literally anything that serves HTML:
XAMPP
Apache/NginxGitHub Pages (yes, it even works there lol)
Or just double-click index.html like a caveman 🪨
4.Create a link with your key:
http://localhost/index.html?Key=Something
5.Send the link to your friends → they type → they send → you get Discord notifications instantly.
## Why not use NGL?

Because NGL looks polished.
And me? I like my tools like I like my humor:
O P E N S O U R C E & S T U P I D

## Hosting Guide (Fake Serious™)

Localhost: Use XAMPP or Apache → copy index.html → done.

GitHub Pages:

Fork repo

Go to repo → Settings → Pages

Enable Pages → pick main branch → /root

Boom, your dumb system is live on the internet.

VPS/Server: Drop it in /var/www/html/ like a pro sysadmin who gave up.

License

MIT License.
Do whatever you want with it.
But seriously, don’t scam people using this potato system.
