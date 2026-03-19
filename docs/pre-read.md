# Pre-Read: SpecKit Hands-on Lab — AI Forward Session

Hi! 👋 You're signed up for the **SpecKit Hands-on Lab** at the AI Forward session. To make the most of our time together, please complete the following setup **before the session**.

---

## What You'll Build

**The $100 Test** — a web app for teams to run prioritization exercises using the well-known "$100 voting" technique. You'll use **SpecKit + Copilot CLI** to add features to an existing app, experiencing spec-driven development firsthand.

---

## Prerequisites (Please Complete Before the Session)

### 1. GitHub Account
- You need a GitHub account with **Copilot access**
- Verify by visiting [github.com/settings/copilot](https://github.com/settings/copilot)

### 2. Git
```bash
winget install --id Git.Git
# Close and reopen your terminal, then:
git --version
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### 3. GitHub CLI
```bash
winget install --id GitHub.cli
# Close and reopen your terminal, then:
gh auth login    # Select GitHub.com, HTTPS, log in via browser
gh --version
```

### 4. VS Code
```bash
winget install --id Microsoft.VisualStudioCode
# Close and reopen your terminal, then:
code --version
```

### 5. Node.js 20 LTS
```bash
winget install --id OpenJS.NodeJS.20
# Close and reopen your terminal, then:
node --version   # Should be v20.x or higher
npm --version
```

### 6. Copilot CLI
```bash
npm install -g @github/copilot
copilot login
copilot --version
```

### 7. Fork & Clone the Starter Repo
```bash
# 1. Fork the repo at https://github.com/bgervin/speckit-jam-starter
#    (Backup if using _microsoft account: https://github.com/agency-microsoft/speckit-jam-starter)
# 2. Clone YOUR fork:
git clone https://github.com/YOUR_USERNAME/speckit-jam-starter.git
cd speckit-jam-starter

# 3. Install dependencies and verify it works:
npm install
npm test          # Should see 30 tests passing
npm start         # Should see "The $100 Test is running at http://localhost:3000"
```

---

## What to Expect

- **Format**: Hands-on lab — you'll be coding along
- **No prior SpecKit experience needed** — we'll walk through it together
- **Bring your laptop** with everything above installed
- **The HOL instructions** will be shared at the start of the session as a web page — no SharePoint access required

---

## Questions?

Reach out if you hit any issues with setup. See you there! 🚀
