# Saathi - Senior Companion App

Hack for a Social Cause, VBYLD 2027 | Theme 9: Elderly Care & Healthy Ageing | Team Impactseekers (HSC|AP|00145), Andhra Pradesh

**Live app:** https://bhumika-glitch.github.io/senior-companion-app/

## Problem
Many senior citizens live alone, miss medicines and pension dates, and feel lonely.

## Features
- SOS with 5-second cancel; opens an SMS with live location and one-tap calls
- Reminders with alarm, voice and notification (pension, check-ups, medicines, schemes)
- Live map with "Take me home", saved daily places, share location
- Volunteer visit log (BP, mood, notes)
- Weekly Day Camps and friends list to reduce loneliness
- Large text, English / Hindi / Telugu, installable app

## Try it in 2 minutes
1. Open the live link and allow location
2. Add an emergency contact, press SOS, then Cancel
3. Reminders tab: add one for 2 minutes ahead and wait for the alarm
4. Switch language from the top dropdown

## Limitations
No server: SOS opens the phone's SMS and the user taps Send. Alarms ring while the app is open or on next opening. Live sharing between phones is planned for the next phase.

## Run locally
`python3 -m http.server 8000` then open http://localhost:8000

## AI Disclosure
Claude (AI assistant) wrote the app code (about 85%) for codes and the first draft of the Hindi and Telugu text. The team created the idea and features, tested on phones, experimented, PPTs, videos and reviewed the text. No AI runs inside the app.

## License
MIT