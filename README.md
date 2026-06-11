# Discord Bot Terms and Policies

This repository is dedicated to hosting the **Terms of Service (ToS)** and **Privacy Policies** for various Discord bots. These pages are statically hosted using GitHub Pages to ensure they are permanently accessible, which is a strict requirement for Discord Bot Verification and acquiring Privileged Intents.

## Hosted Bots

### Ciel
Ciel is a Discord bot designed to provide server utility, statistics parsing, and automated responses (specifically targeting Mazoku bot data).
- **Terms of Service:** [View Terms](https://mims1234.github.io/mydiscordbot-terms-policies/Ciel/terms.html)
- **Privacy Policy:** [View Privacy Policy](https://mims1234.github.io/mydiscordbot-terms-policies/Ciel/privacy.html)

---

## Repository Structure

The repository is structured so that each bot gets its own dedicated directory. This prevents asset conflicts and keeps the URLs clean.

```text
/
├── Ciel/
│   ├── assets/           # Proof of data usage screenshots
│   ├── privacy.html      # Ciel Privacy Policy
│   └── terms.html        # Ciel Terms of Service
└── README.md
```

## How to Add a New Bot
To add policies for another bot in the future:
1. Create a new folder with the bot's name (e.g., `NewBot/`).
2. Add your `terms.html`, `privacy.html`, and any `assets/` into that folder.
3. Commit and push the changes to `main`.
4. The new policies will automatically go live at:
   - `https://mims1234.github.io/mydiscordbot-terms-policies/NewBot/terms.html`
   - `https://mims1234.github.io/mydiscordbot-terms-policies/NewBot/privacy.html`
