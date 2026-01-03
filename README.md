# Hopeful Chat

This is just some random bullshit in an HTML file because I wanted to try out Transformer.js's capabilities. Specifically, I wanted to try to see how I could load an LLM model directly in the user's browser and run it using their GPU.

I also wanted to try out Electron.js and build a desktop app for no damn reason other than to mess around and have fun.

**The LLM is prompted to listen to your current situation (vent to it) and generate a motivational quote.** It uses **SmolLM2 360M**.

> **Warning:** This downloads the model in your browser, so be careful when opening on limited data.

Try the Electron JS app from releases if you wish (Needs Internet on first run to download model, runs offline after that).

## How to Run

### As an Electron App

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the app:
   ```bash
   npm start
   ```

### As a Web Page

Simply open `index.html` in a modern web browser.

## How to Build

To build the Electron app for your platform:

```bash
npm run make
```

The output will be in the `out` folder.
