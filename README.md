# Agent Constitution — Website

Marketing site for [Agent Constitution](https://agentconstitution.com), the iOS app that lets you define behavioral rules for your AI agents.

## What is Agent Constitution?

Agent Constitution gives you control over what your AI agents can and can't do. Define rules, get push notifications when an agent tries a restricted action, and approve or deny from your iPhone. Full audit trail of every decision.

## Structure

```
index.html      — Main landing page
privacy.html    — Privacy policy
terms.html      — Terms of service
support.html    — Support & FAQ
security.html   — Security architecture
css/style.css   — Styles (dark theme, purple accent)
img/            — SVG icons
CNAME           — GitHub Pages custom domain
```

## Development

Just open `index.html` in a browser. No build step required.

```bash
# Local server
python3 -m http.server 8000
```

## Deployment

Hosted on GitHub Pages with custom domain `agentconstitution.com`.

## Built With

- Pure HTML + CSS (no JavaScript frameworks)
- Dark theme with purple (#6C63FF) accent
- Responsive design
- Terminal/monospace aesthetic

## Links

- **App**: Coming soon on the App Store
- **Relay**: [github.com/arunrlverma/relay4agents](https://github.com/arunrlverma/relay4agents)
