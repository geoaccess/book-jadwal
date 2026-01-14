[Uploading README.md…]()
# Geoaccess Private Training - Booking System

A scheduling web application for Geoaccess private GIS training sessions.

## Features

- 📝 Client registration with email lookup
- 👥 Tutor-client assignment from Google Sheets
- 📅 Calendar-based scheduling
- ⏰ Automatic reminders (1 day & 3 hours before)
- 📱 Google Calendar integration
- 🔧 Admin dashboard

## Live Demo

Visit: https://geoaccess.github.io/book-jadwal

## Data Source

Client-tutor assignments are managed via Google Sheets:
- [View Spreadsheet](https://docs.google.com/spreadsheets/d/1dsNf_lNB6k2TmOAmSdyvrcjMNEvvbz1dVXhGBZ7hDEc/edit)

## Development

```bash
# Install dependencies
npm install

# Run locally
npm start

# Build for production
npm run build

# Deploy to GitHub Pages
npm run deploy
```

## Deployment

This app is configured to deploy to GitHub Pages automatically using:
```bash
npm run deploy
```

## Tech Stack

- React 18
- Google Sheets API (for client data)
- Google Calendar API (for scheduling)
