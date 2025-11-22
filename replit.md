# labs.maniadhikari.com - Coming Soon Page

## Overview
This is a static "coming soon" landing page for labs.maniadhikari.com. The page features a modern design with an animated gradient background and a waitlist signup form for users interested in free Webflow tools and experiments.

## Project Type
- **Type**: Static HTML/CSS/JavaScript website
- **Purpose**: Coming soon landing page with waitlist functionality
- **Framework**: Vanilla HTML/CSS/JS (no framework)

## Structure
```
.
├── index.html          # Main landing page
├── server.py           # Simple Python HTTP server for development
├── README.md           # Project documentation
├── .gitignore          # Git ignore file
└── replit.md           # Replit project documentation
```

## Features
- Modern, animated gradient mesh background
- Email waitlist signup form
- LocalStorage-based subscription state tracking
- Social proof counter
- Fully responsive design
- Social media links in footer

## Development Setup
- **Server**: Python 3.11 HTTP server
- **Port**: 5000 (frontend)
- **Host**: 0.0.0.0 (to support Replit's proxy)
- **Workflow**: "Web Server" running `python server.py`

## Deployment Configuration
- **Deployment Type**: Static
- **Public Directory**: . (root directory)
- The site is ready to publish as a static website

## Recent Changes
- **2025-11-22**: Initial import and Replit environment setup
  - Installed Python 3.11 for development server
  - Created `server.py` with cache-control headers for development
  - Configured workflow to run on port 5000 with webview output
  - Added deployment configuration for static hosting
  - Created .gitignore for Python files

## Technical Notes
- The form currently uses localStorage to track subscriptions (client-side only)
- The JavaScript simulates form submission - in production, this should be connected to a real backend or service
- Cache-Control headers are disabled in the development server to ensure changes are visible immediately
- The site is purely static HTML/CSS/JS with no build process required

## User Preferences
None recorded yet.

## Project Architecture
This is a single-page application with no backend. The waitlist form submission is currently handled with client-side JavaScript and localStorage. To make this functional in production, the form should be integrated with an email service or backend API.
