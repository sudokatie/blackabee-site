# blackabee-site

Landing page for [blackabee.com](https://blackabee.com).

Minimal terminal-aesthetic portfolio showcasing open source projects.

## Stack

- Static HTML/CSS
- Hosted on nginx
- Let's Encrypt SSL

## Design

- Monospace typography (SF Mono, Fira Code, Consolas)
- Black/white color scheme
- Square corners, no rounded elements
- No emojis
- Mobile responsive

## Deploy

```bash
scp index.html katie-server:/var/www/blackabee/
```

Server: katie-server (68.183.169.72)
Path: `/var/www/blackabee/` (NOT /var/www/html/)
Site: https://blackabee.com

## License

MIT
