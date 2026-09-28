# FUT Fox — Chrome Extension

**A Gallery planner and transfer-market sniper for the EA FC web app.**

Chrome only installs extensions in one click from its Web Store. This one is
not there, so it goes in by hand — four steps, once.

## 🚀 Get started in 4 steps

### Step 1: Download it

<a href="https://github.com/Emreisik46/Fut-Sniper-Chrome-Extension/raw/main/fut-fox.zip">
  <img src="https://img.shields.io/badge/Download-FUT%20Fox-ff7a1a?style=for-the-badge" alt="Download FUT Fox">
</a>

That link always gives you the newest version.

### Step 2: Extract it

- **Windows**: right-click the zip → *Extract All*
- **Mac**: double-click it

Put the folder somewhere you will leave alone — **Chrome loads it from where it
sits**, so deleting or moving it later removes the extension.

### Step 3: Load it in Chrome

1. Go to `chrome://extensions`
2. Turn on **Developer mode**, top right
3. Click **Load unpacked**
4. Pick the extracted folder — the one with `manifest.json` in it

### Step 4: Sign up and go

1. Click the fox in Chrome's toolbar and make an account
2. Open the [FC Ultimate Team Web App](https://www.ea.com/ea-sports-fc/ultimate-team/web-app/)
3. **Gallery** and **Sniper** are in the left menu

## 🔄 Updating

**Nothing to do.** The planner and the sniper are fetched fresh every time you
open the web app, so improvements reach you on the next page load — no
re-downloading, no reinstalling.

Only the extension's shell changes rarely, and if it ever does you will be told
to grab this again. Otherwise you can forget this page exists.

## 🎯 What it does

**Gallery** works out what your coins can earn: which sets to do, at which
grade, in what order, and what each costs after EA's 5% tax. Prices come live
from the transfer market, so they are what cards actually cost right now, not
a cached guess.

**Sniper** sits inside EA's own *Search the Transfer Market* screen, so you
snipe with every filter EA has. Set a Max Buy Now, press <kbd>Space</kbd>, and
it searches and buys on its own until you stop it — one card a try, the
cheapest at or under your max, then listed at your price or sent to your club.

## ❓ Trouble

| | |
|---|---|
| **Nothing in the menu** | Reload the FUT web app page. The panel is fetched at load. |
| **Extension vanished** | You moved or deleted the folder. Chrome loads it from where it sits — extract it again. |
| **Can't sign in** | Message whoever gave you this — they can send you a link to set a new password. |
| **It won't load at all** | The server may be down. Try again shortly. |

## ⚠️ Worth knowing

- **The server has to be up.** The panel is fetched rather than bundled, which
  is what makes updates automatic; if the server is down, nothing appears.
- **Automating the web app is against EA's terms.** The Sniper searches and
  buys on its own, which is what EA means by a bot. The risk to your account is
  yours.
