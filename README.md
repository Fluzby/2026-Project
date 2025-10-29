# Construction Vehicle Tracker
---

## Live Demo
-

---

## Roadmap

### Phase 1: Buy & Setup AirTags (Week 1)
- [ ] Buy 10+ AirTags (€29 each on Amazon)
- [ ] Create Apple ID: example@mail.com
- [ ] Pair all AirTags to this ID
- [ ] Hide in vehicles:
  - Under seat
  - OBD port
  - Tool box
- [ ] Label: VEH-01, VEH-02, etc.

---

### Phase 2: Simple Website (Week 1–2)
frontend/index.html
- [ ] HTML + Tailwind CSS (CDN)
- [ ] Mapbox or Google Maps (free tier)
- [ ] Static pins (for testing)
- [ ] Vehicle list on left
- [ ] Mobile-friendly

---

### Phase 3: Connect AirPinpoint API (Week 2)
backend/server.js
- [ ] Sign up: https://airpinpoint.com
- [ ] Add AirTags in dashboard
- [ ] Get API Key
- [ ] Build /api/vehicles endpoint
- [ ] Poll every 60s → return:
  {
    "id": "VEH-01",
    "lat": 40.7128,
    "lng": -74.0060,
    "battery": 92,
    "timestamp": "2025-04-05T12:00:00Z"
  }
- [ ] Deploy free: Render (render.com) or Railway (railway.app)

---

### Phase 4: Live Website (Week 3)
- [ ] Frontend fetches /api/vehicles every 30s
- [ ] Update map pins in real-time
- [ ] Show battery + last seen
- [ ] Click vehicle → zoom
- [ ] Add "Last Updated" badge

---

### Phase 5: Pro Features (Week 4+)
- [ ] Geofencing (yard alerts)
- [ ] 24h location history
- [ ] Export to CSV
- [ ] Password protect site
- [ ] SMS/email alerts via webhook

---

## Repo Structure
construction-airtag-tracker/
├── frontend/
│   └── index.html
├── backend/
│   └── server.js
├── .gitignore
├── README.md
└── deploy.md

---

## Quick Start

1. Buy & pair AirTags → Add to AirPinpoint
2. Get API Key
3. Edit backend/server.js → add your API_KEY
4. Deploy backend → get public URL
5. Update frontend/index.html → set API_URL
6. Push & enable GitHub Pages

Done! Open in browser — see your fleet live.

---

## Tech Stack
- Tracking: Apple AirTags + AirPinpoint API
- Frontend: HTML, JS, Mapbox
- Backend: Node.js (Express)
- Hosting: GitHub Pages + Render/Railway

---

## Costs
- AirTags: €29 each
- AirPinpoint: Free up to 32 tags
- Hosting: Free

---

Total Time: 3–4 weeks  
Total Cost: ~€300 for 10 vehicles

---

