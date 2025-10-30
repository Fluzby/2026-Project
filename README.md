<img width="607" height="434" alt="image" src="https://github.com/user-attachments/assets/cd6b0503-6774-4460-a96c-67f00d34ea27" /># Construction Vehicle Tracker

---

## Develop a mobile and/or web application for a construction company to:
- Track the real-time location of construction vehicles.
- Alert administrators instantly if a vehicle leaves its designated work zone (geo-fencing for anti-theft protection).
- Allow customers to track delivery vehicles in real time and see the estimated distance/time until arrival.
<img width="607" height="434" alt="image" src="https://github.com/user-attachments/assets/94025627-785b-43bd-9420-4b9e006879bc" />
<img width="610" height="405" alt="image" src="https://github.com/user-attachments/assets/4739f2a1-237d-4cce-8d3f-1b729f4ce74c" />


---

## Roadmap

### Phase 1: Buy & Setup AirTags (Week 1)
- [ ] Buy 10+ AirTags (€29 each on Amazon)
- [ ] Create a work Apple ID: example@mail.com
- [ ] Pair all AirTags to this ID
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

### Phase 4: Live Website (Week 3-4)
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
- [ ] Try to make it a full app store app

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
- Apple App Store fee developer €99

---

Total Time: 3–4 weeks  
Total Cost: ~€300 for 10 vehicles

---

## Helpful links
- https://airpinpoint.com/
- https://www.itslaut.com/collections/case-for-airtag/products/bike-tag-bottle-mount-for-airtag
- https://www.apple.com/airtag/

