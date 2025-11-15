# view-transitions-api-demo

A demo project showcasing the [View Transitions API](https://developer.mozilla.org/en-US/docs/Web/API/View_Transitions_API) in modern browsers.  
This repository provides two modes: a **Multi-Page App (MPA)** and a **Single Page App (SPA)** implementation to compare patterns.
Also **None** repository is an empty boilerplate that makes you apply view transitions

## 🧰 Contents

- `mpa/` — Cross document view transitions (multi-page-MPA).
- `spa/` — Same document view transitions (single-page-app).
- `none/` — Not implemented View transitions as boilerplate.  
- `products.json` — Contains products and its informations in the list.  

## 🎯 Features

- Uses the View Transitions API to provide smooth transitions between sections/pages.  
- Demonstrates how to integrate the API in both MPA and SPA scenarios.  
- Lightweight, no heavy framework required for the MPA version.
- Using native HTML/CSS/JS
- Simple routing logic in the SPA version to illustrate navigation + transition handling.

## 🚀 Getting Started

### Prerequisites

- A modern browser with View Transitions API support (e.g., recent Chrome/Edge versions).  
- Basic web server to serve files (static server) for best results (some features may not work via `file://`).

### Running Locally

1. Clone the repo  
   ```bash
   git clone https://github.com/mertmtn/view-transitions-api-demo.git
   cd view-transitions-api-demo
2. Navigate to the mode you want to try
   ```bash
   # For Multi-Page App
   cd mpa
   # OR for Single Page App
   cd spa
3. Run a simple static http server
   ```bash
   npx http-server . -c-1

4. Interact with the demo: navigate between pages/sections and observe the transitions.

📚 Resources

MDN Docs: https://developer.mozilla.org/en-US/docs/Web/API/View_Transition_API

View Transitions - Bramus's Blog https://view-transitions.chrome.dev/

Google for developers: https://developer.chrome.com/docs/web-platform/view-transitions

Examples & patterns from the communites' blogs or videos

📝 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute it.
