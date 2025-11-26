---
# FriendlyStay — Conversational Hotel Booking

FriendlyStay is a single-page web application that turns hotel booking into a friendly, conversational experience. Powered by **Mira**, an empathetic  guide, the app uses principles from **CASA (Computers as Social Actors)** to create warm, human-like interactions.
---

## 🌟 Features

### Conversational Experience

- Chat-driven flow with Mira
- Friendly, emoji-enhanced responses
- Animated avatar + online status
- Polite, empathetic error handling

### Smart Hotel Browsing

- 20 hotels across 6 categories
- Randomized, non-repeating hotel selection
- Clear availability states
- Filters: price, rating, category, amenities
- Review modals (3 reviews per hotel)
- Side-by-side hotel comparison

### Modern UI/UX

- Gradient design + smooth animations
- Responsive layout
- Accessible tooltips & modals
- Fully client-side (no backend)

## 📘 How to Use

1. Enter destination
2. Select dates
3. View 3 hotel suggestions
4. Apply filters (optional)
5. Read reviews or compare hotels
6. Book rooms & extras
7. Confirm and restart

---

## 🧩 Tech Overview

- **HTML5**, **CSS3**, **JavaScript (ES6+)**
- **Tailwind CSS** (CDN)
- All logic contained in `index.html`
- Key features handled by functions such as:

  - `showHotels()`
  - `applyFilterSettings()`
  - `compareSelected()`
  - `confirmBooking()`

---

## 🏨 Hotel Data Example

```javascript
{
  id: 1,
  name: "Cozy Corner Inn",
  price: 89,
  rating: 4.5,
  amenities: ["wifi", "parking", "breakfast"],
  availability: "Available",
  userReviews: [...]
}
```

---

## 🔮 Roadmap

- Backend integration
- Payment support
- User accounts
- Multi-language mode
- Voice interaction
- Map view & photo galleries
- Mobile app

---
