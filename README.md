# onion-node

Lightweight, zero-JavaScript static frontend built for an experimental Tor v3 hidden service (`.onion`) mirror.

## Stack & Infrastructure
- **Frontend:** Pure HTML5 & CSS3 (no external CDNs, trackers, or client-side JS)
- **Server:** AWS EC2 (Ubuntu 24.04 LTS)
- **Web Server & Routing:** Nginx reverse/static config routed via Tor v3 hidden service

## Pages Included
- `index.html` — Node overview
- `projects.html` — Active builds and experiments
- `logs.html` — Lab notes and setup updates
- `about.html` & `contact.html` — Info and public contact

## Purpose
Built as a hands-on Linux server administration, Nginx configuration, and privacy-oriented networking lab.
