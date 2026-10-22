<pre>
      ( ^_^)  hi, I'm hidecs
       /|\    ask me anything
       / \    [ ... ]
  ┌─────────────────────┐
  │  ░░░░░░░░░░░░░░░░░░  │
  └─────────────────────┘
</pre>

# hidecs-chatbot

An early scaffold for a conversational assistant for the HIDECS project, built on top of Create React App.

## What it is

This is the starting point for a chat interface meant to talk to a GPT-style API — the shell a front-end chatbot would be built inside. Right now it's the unmodified Create React App template: a single component, the default logo and styles, nothing wired up yet. No API key, request logic, or chat UI has been added — this repo does not ship or include any credentials.

## Stack

React 18, Create React App 5 (`react-scripts`), Jest/Testing Library for the default test setup.

## Run locally

```bash
npm install
npm start      # dev server at http://localhost:3000, hot reloads on save
npm test       # interactive test runner
npm run build  # production build to ./build
```

To build this into an actual chatbot, you'd add your own API key as an environment variable (never commit it) and wire a request layer into `src/App.js`.

## Map

```text
src/
├── App.js        # root component (currently the CRA starter screen)
├── App.css
├── index.js       # React entry point
└── reportWebVitals.js, setupTests.js   # CRA defaults
public/
└── index.html, manifest.json, icons    # CRA static shell
```
