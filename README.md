# Western Ghats Tourism Website

**Tagline:** One State, Countless Journeys

A modern, responsive tourism website dedicated to exploring the breathtaking Western Ghats region of India. Built with a premium, nature-inspired aesthetic and seamless user experience.

## Features

- 🏔️ Multi-page responsive design
- 🎥 Full-screen hero sections with video backgrounds
- 📍 20+ Major destinations with detailed pages
- 🖼️ Gallery with lightbox and lazy loading
- 🎫 Integrated booking system
- 📱 Mobile-first responsive design
- ⚡ Fast loading with optimized images
- 🌿 Nature-inspired design (forest greens, earthy browns)

## Tech Stack

**Frontend:**
- HTML5
- CSS3 (with animations & transitions)
- JavaScript (Vanilla JS + Libraries)
- React.js (for interactive components)

**Backend:**
- Node.js / Express.js
- REST API

**Database:**
- MongoDB

## Destinations Covered (20+)

### Karnataka (Western Ghats)
1. **Coorg** - Coffee plantations & adventure
2. **Chikmagalur** - Trekking & coffee trails
3. **Sakleshpur** - Hidden gem with forts
4. **Agumbe** - Monsoon experience
5. **Shimoga** - Forest & waterfalls
6. **Jog Falls** - Majestic waterfalls
7. **Kudremukh** - Peak trekking

### Kerala (Western Ghats)
8. **Wayanad** - Forests & culture
9. **Munnar** - Tea gardens
10. **Valparai** - Quiet escape
11. **Idukki** - Dams & views
12. **Thekkady** - Wildlife sanctuary
13. **Kottayam** - Backwaters
14. **Kasaragod** - Northern gateway

### Tamil Nadu (Western Ghats)
15. **Ooty** - Queen of hill stations
16. **Kodaikanal** - Princess of mountains
17. **Coonoor** - Toy train rides
18. **Conoor** - Trekking hub
19. **Nilgiri Hills** - Scenic beauty
20. **Avalanche Peak** - Adventure

### Maharashtra (Western Ghats)
21. **Mahabaleshwar** - Pilgrimage & nature
22. **Panchgani** - Twin lakes
23. **Satara** - Historical sites
24. **Raigad** - Fort trekking

## Project Structure

```
toursim/
├── public/
│   ├── index.html
│   ├── images/
│   ├── styles/
│   └── favicon.ico
├── src/
│   ├── js/
│   ├── styles/
│   └── components/
├── server/
│   ├── models/
│   ├── routes/
│   └── server.js
├── docs/
│   ├── SETUP.md
│   └── DESTINATIONS.md
└── package.json
```

## Getting Started

### Prerequisites
- Node.js (v14+)
- npm or yarn
- MongoDB

### Installation

```bash
git clone https://github.com/yoganandahruthik-afk/toursim.git
cd toursim

npm install
cp .env.example .env

npm run dev
```

Server runs at `http://localhost:5000`

## Design Features

- **Nature-Inspired**: Forest greens, earthy browns, misty overlays
- **Premium Feel**: Luxury travel aesthetic
- **Responsive**: Mobile-first design
- **Performance**: Lazy loading, optimized images
- **Smooth Animations**: Scroll animations & transitions

## API Endpoints

- `GET /api/destinations` - All destinations
- `GET /api/destinations/:id` - Specific destination
- `POST /api/bookings` - Create booking
- `GET /api/gallery` - Gallery images

## Contributing

Contributions welcome! Submit pull requests following coding standards.

## License

MIT License

## Contact

📧 Email: tourism@example.com
🌐 Website: Coming soon

---

**One State, Countless Journeys! 🏔️**
