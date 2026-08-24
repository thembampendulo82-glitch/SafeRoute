SafeRoute 🗺️

**A community-powered safety mapping app for streets that don't show up on any map.**

## Problem

Millions of people in underserved communities navigate roads and paths every day without knowing which routes are actually safe. Broken streetlights, flooded roads, and high-risk areas go unreported and invisible to city services — until someone gets hurt. Existing map apps optimize for the *shortest* route, not the *safest* one.

## Solution

SafeRoute lets learners, commuters, and vendors report unsafe areas, broken streetlights, and flooded roads in real time using GPS and crowdsourced data. The app then suggests the safest walking route — not just the shortest — using this live community data. It's built to work offline and on low data, so it's usable in the communities that need it most.

## Who Benefits

- **Commuters and learners** walking to school, work, or transit stops
- **Vendors and informal traders** navigating routes daily with goods
- **Local communities** who gain visibility into service delivery failures (unsafe roads, broken infrastructure) that are otherwise invisible to authorities

## Tech Stack

- **Mapping:** Leaflet.js, Mapbox, OpenStreetMap
- **Frontend:** React
- **Backend/Data:** Node.js, PostGIS
- **Storage/Realtime:** Firebase
- **Low-data access:** WhatsApp / USSD API (for offline/low-connectivity reporting)

## Next Steps

- [ ] Build MVP map screen with live hazard reporting (Figma prototype)
- [ ] Implement safest-route algorithm using crowdsourced hazard data
- [ ] Set up WhatsApp/USSD reporting flow for low-data users
- [ ] Pilot test with a small community group and gather feedback

---
*Prototype in progress — built for Sonke Platform by The innovators.*
