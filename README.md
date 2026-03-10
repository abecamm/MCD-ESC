# MCD Auto-Responder 📋

Automates Mobile Check Deposit (MCD) escalation responses for Banking Risk Ops.

## What It Does

Two browser bookmarklets that automate the MCD escalation workflow:

1. **① Regulator → Toolbox 🚀** - Extracts GMB token from Regulator, copies to clipboard, opens Toolbox
2. **② Get Template 📋** - Extracts decline reason from Toolbox, looks up template (52 codes), shows popup with one-click copy

## Time Savings

| Metric | Before | After |
|--------|--------|-------|
| Per escalation | ~110 sec | ~10 sec |
| Daily (10 cases) | ~18 min | ~1.7 min |
| Monthly | ~6 hours | ~34 min |

## Installation

1. Open `index.html` in your browser (or visit the [GitHub Pages site](https://abecamm.github.io/mcd-auto-responder/))
2. Show your bookmarks bar (`Cmd+Shift+B`)
3. Drag both buttons to your bookmarks bar
4. Done!

## Usage

1. Get escalation in Slack with Regulator link
2. Open the Regulator page
3. **Click blue bookmark** → GMB token copied, Toolbox opens
4. **Paste** (`Cmd+V`) in Toolbox → click "Get Check"
5. **Click green bookmark** → template appears in popup
6. **Click "Copy to Clipboard"** → paste in Slack
7. Done! 🎉

## Coverage

- **52 depository codes** (Manual + Automated)
- **35 Manual rejection codes**
- **12 Automated rejection codes**
- **5 Legacy/alternate codes**

## Team

Banking Risk Ops - Abraham Camacho & Lindsey Pellegrini

## Version

v3.0 - March 2026
