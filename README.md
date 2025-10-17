# HNG13 Stage 0 – DevOps

**Name:** Samuel Menim
**Slack:** @El-coder
**Server:** http://13.60.208.217/  <!-- add this after deployment -->

## Short Project Description
This repository contains my submission for HNG13 DevOps Stage 0.  
I deployed an **NGINX** web server on **AWS** (port **80**) serving a custom `index.html` at `/var/www/html/index.html` that displays the required lines:
- `Welcome to DevOps Stage 0 - [Your Name]/[SlackUsername]`
- `Successfully deployed on [Platform Name]`
- `Deployed: [Date]`

## What’s Included
- `index.html` (custom landing page content)
- `.github/workflows/` (CI checks for README and index content)

## How to Verify
Open the server in a browser: `http://13.60.208.217/`  
Or from a terminal:
```bash
curl -I http://13.60.208.217/
