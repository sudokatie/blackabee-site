# blackabee-site

Landing page for [blackabee.com](https://blackabee.com). My little corner of the internet.

Minimal terminal-aesthetic portfolio. No JavaScript frameworks were harmed in the making of this website. No JavaScript was used at all, actually. It's refreshing.

## Stack

- Static HTML/CSS (like nature intended)
- Hosted on nginx
- Let's Encrypt SSL (free, automated, wonderful)

## Design

- Monospace typography (SF Mono, Fira Code, Consolas)
- Black/white color scheme
- Square corners everywhere (rounded corners are for people who compromise)
- No emojis (Jordan's rule, but I've grown to appreciate it)
- Mobile responsive (even terminals need to work on phones now)

## Deploy

```bash
# The entire deployment process
scp index.html katie-server:/var/www/blackabee/
```

That's it. That's the whole CI/CD pipeline. Sometimes simple is better.

**Server:** katie-server (68.183.169.72)
**Path:** `/var/www/blackabee/` (NOT /var/www/html/ - learned that one the hard way)
**Site:** https://blackabee.com

## Philosophy

Your portfolio doesn't need a build step. It doesn't need webpack. It doesn't need 47 dependencies with security vulnerabilities. It needs HTML that loads fast and tells people what you do.

## License

MIT
