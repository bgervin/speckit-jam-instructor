# Pre-Read: SpecKit Hands-on Lab — AI Forward Session

Hi! 👋 You're signed up for the **SpecKit Hands-on Lab** at the AI Forward session. To make the most of our time together, please complete the following setup **before the session**.

---

## What You'll Build

**The $100 Test** — a web app for teams to run prioritization exercises using the well-known "$100 voting" technique. You'll use **SpecKit + GitHub Copilot CLI** to add features to an existing app, experiencing spec-driven development firsthand.

---

## Prerequisites (Please Complete Before the Session)

### 1. GitHub Account
- You need a GitHub account with **Copilot access**
- Verify by visiting [github.com/settings/copilot](https://github.com/settings/copilot)

### 2. GitHub CLI + Copilot CLI
```bash
# Install GitHub CLI: https://cli.github.com/
gh auth login
gh extension install github/gh-copilot

# Verify
ghcs --version
```

### 3. VS Code
- Download from [code.visualstudio.com](https://code.visualstudio.com/)

### 4. Node.js (v18 or later)
```bash
# Download from https://nodejs.org/
node --version   # Should be 18.x or higher
```

### 5. Fork & Clone the Starter Repo
```bash
# 1. Fork the repo at https://github.com/bgervin/speckit-jam-starter
# 2. Clone YOUR fork:
git clone https://github.com/YOUR_USERNAME/speckit-jam-starter.git
cd speckit-jam-starter

# 3. Install dependencies and verify it works:
npm install
npm test          # Should see 25 tests passing
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
