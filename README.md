# AP® Score Cheeser

Look, you know why you're here. You want to cheese your AP® scores. To prevent you from hurting yourself with inspect element (which can refresh the scores when you close dev tools, resize the window, click a link, or whenever the website just feels like it), I'll make it super simple for you. Once you've [installed this userscript](#-installation), click and hold on a score you want to change, enter a new number you want to show up for that score. If you want to set all scores (including future ones), type "all n" (without quotes) where 'n' is a new number. If you want to reset that score to whatever you _really_ got, type "reset". If you want to reset every score, type "reset all" or "all reset".

## 🎥 Demo

(sped up 2x)

<p align="center">
  <a href="demo-1.0.0.gif">
    <img src="demo-1.0.0.gif" />
  </a>
</p>

## ⚡️ Is this a virus?

Nope! Anyone that understands basic English can understand the script.

The code:

- 🔓 is 100% open source (because it needs to be so you can install it)
- 🔍 has very detailed comments on almost each line
- 🔒 only runs on the specific AP® Scores page
- 📶 makes no network requests
- 👨‍💻️ is written in JavaScript
- 💻 can't do anything to your computer

## 📜 Installation

- Install Tampermonkey from the [Chrome Web Store](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) (or [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/))
- After this, you have two options (only do one of these):
  - **GreasyFork** _(recommended)_: Go to the [GreasyFork page](https://greasyfork.org/en/scripts/470198-ap-score-cheeser) and click the green "Install this script" button. This will take you to a page on Tampermonkey where you need to click "Install" to install the script.
  - **GitHub/Manual install** _(not recommended)_: Go to the [raw script page](https://raw.githubusercontent.com/Samathingamajig/ap-score-cheeser/main/ap-score-cheeser.user.js). Tampermonkey will automatically detect this file as a userscript (since the file is named `*.user.js`), so click the "Install" button to install it. If it doesn't, copy the entire contents of the script into the Tampermonkey script editor (**make sure you save**).
  - If none of these work, look up how to install a Tampermonkey userscript.

## 🎉 Notice when using with AP® Score Hider

I've made another project recently called AP® Score Hider (https://github.com/Samathingamajig/ap-score-hider) which hides your scores until you click on them, blasts confetti for passing scores, and plays (optional) customizable sound effects based on the score. If you're using both at the same time, there's one issue currently that I've found that's not easily fixable:

- Wait a few seconds after the page becomes visible again to guarantee scores change. If you reveal a score too quickly, it might not have changed yet.

## 🚫 Uninstallation

If you don't want to use this script anymore, you can uninstall it anytime.

- Navigate to the Tampermonkey dashboard (click the extension icon in the top right, then click "Dashboard" at the bottom of the popup)
- Click the trashcan on the right side of the page on the row with "AP® Score Cheeser"

AP® is a trademark registered by the College Board, which is not affiliated with, and does not endorse, this product.
