# athuljothi-abhijith — Wedding Invitation

A luxury, interactive wedding invitation web application built with **React.js** and **Vite**, featuring traditional Kerala Kasavu styling, golden theme, interactive 3D envelope opening animation, chibi couple animations, countdown timer, event schedules, and Google Maps integration.

## ✨ Features

- **Interactive 3D Envelope**: Tap or press Enter to unseal the envelope and reveal the golden wedding card.
- **Animated Chibi Couple Stage**: Handcrafted running chibi animations for the groom and bride meeting with a heartwarming hug and floating hearts (tap to replay anytime).
- **Kerala Kasavu Motif**: Elegant Kasavu gold borders and royal deep theme with Cinzel, Cormorant Garamond, and Italianno typography.
- **Event Switcher / Query Param Support**:
  - `?type=all`: Shows both the **Wedding Ceremony (Muhurtham)** at BAMAS Auditorium and the **Wedding Reception** at White Rose Convention Centre.
  - `?type=ceremony`: Shows the Wedding Ceremony only.
  - `?type=reception`: Shows the Wedding Reception only.
  - Includes an interactive floating view pill (`View: All | Ceremony | Reception`) to preview modes instantly.
- **Interactive Countdown**: Vintage torn-paper flip cards counting down in real-time to August 28, 2026.
- **Venue & Google Maps**: Direct one-click location links to both venues on Google Maps.
- **RSVP & Contact**: One-tap phone call button to RSVP.

## 🚀 Getting Started

### 1. Install dependencies:
```bash
npm install
```

### 2. Run local development server:
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) or [http://localhost:3000/?type=all](http://localhost:3000/?type=all) in your browser.

### 3. Build for production:
```bash
npm run build
```
The optimized production build will be generated in the `dist/` directory, ready to deploy to Vercel, Netlify, or GitHub Pages.

## 📁 Project Structure

```
├── public/
│   ├── assets/
│   │   ├── boy_chibi.png
│   │   ├── girl_chibi.png
│   │   └── couple_hug_chibi.png
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Petals.jsx           # Floating golden petals background
│   │   ├── IntroEnvelope.jsx    # 3D interactive opening envelope
│   │   ├── CoupleStage.jsx      # Animated groom & bride chibi running and hugging
│   │   ├── Hero.jsx             # Hero section with couple stage, names & date
│   │   ├── Families.jsx         # Groom & bride family details
│   │   ├── Events.jsx           # Muhurtham ceremony & reception cards
│   │   ├── Countdown.jsx        # Real-time torn-paper flip countdown
│   │   ├── RSVPFooter.jsx       # Call to RSVP and calligraphy footer
│   │   └── ModeTogglePill.jsx   # Floating view mode toggle pill
│   ├── data/
│   │   └── weddingData.js       # Complete configuration & wedding details
│   ├── App.jsx                  # Main application orchestrator
│   ├── index.css                # Luxury gold/dark Kerala aesthetics & keyframe animations
│   └── main.jsx                 # React root entrypoint
├── index.html
├── vite.config.js
└── package.json
```
