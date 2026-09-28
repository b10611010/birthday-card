# 🎂 Birthday Card

An animated birthday card web page, built with plain HTML, CSS, and JavaScript. No frameworks or installs needed.

🔗 **Live page:** https://b10611010.github.io/birthday-card/

## Scan to open

<img src="qr-code.png" alt="QR code linking to the birthday card" width="220">

## Features

- Animated gradient background
- Floating balloons and falling confetti
- Pop-in card with a wiggling cake
- "Celebrate" button that triggers a confetti and balloon burst
- Responsive layout that works on phones and computers
- Automatic light and dark mode

## Project structure

```
birthday-card/
├── index.html    # the whole card: HTML, CSS, and JavaScript in one file
├── qr-code.png   # QR code that links to the live page
└── README.md     # this file
```

## Customize the message

Open `index.html` and find these two lines inside the `<script>` block:

```js
const RECIPIENT_NAME = "Name here";
const MESSAGE = "Your message here";
```

Replace the text between the quotes and save. The name and message are filled into the card automatically.

To change the look, edit the color variables at the top of the `<style>` block:

```css
--bg1:#ff9a9e; --bg2:#fecfef; --bg3:#a18cd1;   /* background gradient */
--accent:#ff6f91;                              /* heading and button */
```

## Run locally

Double-click `index.html` to open it in your browser. No server is required.

## Deploy with GitHub Pages

1. Push the files to a GitHub repository. The main page must be named `index.html`.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`, and click **Save**.
4. After a minute or two, the site is live at `https://<username>.github.io/<repo-name>/`.

After each edit, hard-refresh the page (Ctrl+Shift+R, or Cmd+Shift+R on Mac) to skip the browser cache.

## Note

Because this repository is public, anyone with the link can read the message in the page source.
