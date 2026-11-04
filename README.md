# CoopWatch

CoopWatch is a responsive poultry-house temperature and humidity dashboard. It opens in demo mode and can connect to a ThingSpeak channel for live readings.

## Live data

Select **Data source** and enter your channel ID. For private channels, use a ThingSpeak **Read API key** only. Never publish a Write API key or other secret in this public repository.

## Run locally

Open index.html in a browser or serve this folder over HTTP. The PWA service worker requires HTTPS or localhost.

## GitHub Pages

This repository publishes from the root of the main branch. The public website is at https://abdulmuzillu55.github.io/coopwatch-pwa/.

The dashboard is public and does not provide authentication. Live data and alerts require an internet connection and the page to remain open.
