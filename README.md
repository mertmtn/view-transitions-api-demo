# view-transitions-api-demo

A demo project showcasing the [View Transitions API](https://developer.mozilla.org/en-US/docs/Web/API/View_Transitions_API) in modern browsers.  
This repository provides two modes: a **Multi-Page App (MPA)** and a **Single Page App (SPA)** implementation to compare patterns.

## 🧰 Contents

- `mpa/` — A simple multi-page implementation using native HTML/CSS/JS.  
- `spa/` — A SPA implementation (e.g. using client routing) demonstrating how the API works in a single-page context.  
- `none/` — Not implemented View transitions as boilerplate.  
- `products.json` — Contains products and its informations in the list.  

## 🎯 Features

- Uses the View Transitions API to provide smooth transitions between sections/pages.  
- Demonstrates how to integrate the API in both MPA and SPA scenarios.  
- Lightweight, no heavy framework required for the MPA version.  
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
3. Run a simple static server
4. Interact with the demo: navigate between pages/sections and observe the transitions.
