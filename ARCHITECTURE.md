# Architecture

Saathi is a single-page web app (HTML + CSS + JavaScript) with no backend in this prototype.

| Part | Technology | Purpose |
|---|---|---|
| UI | HTML/CSS, large touch targets, A+ text mode | Elderly-friendly interface |
| Storage | Browser localStorage | Contacts, reminders, visit logs, places |
| Location | Browser Geolocation API | Live location, daily path |
| Map | Leaflet + OpenStreetMap | Map display, home marker |
| Alarms | setInterval + Web Audio + Speech Synthesis + Notification API | Reminders with sound and voice |
| SOS | SMS/tel links with location link | Alert family without a server |

## Phase 2 (planned)
- Backend (Firebase/Node) for real push alerts and live location sharing between devices
- Offline map tiles for the user's city
- Volunteer and family logins
- More regional languages 