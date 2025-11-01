# WalkMate – Safe Walks Together 🔐

A modern, calm safety companion web application for night walks with real-time tracking, emergency features, and community safety tools.

![WalkMate](ICON.jpg)

## ✨ Features

### 🏠 Home Page
- Interactive OpenStreetMap with route planning
- From/To location search (India-focused)
- Live walk tracking with GPS simulation
- Real-time timer (MM:SS format)
- Route visualization with OSRM routing

### 🚨 Emergency Features
- **SOS Button**: Emergency alerts with contact notification
- **Emergency Contacts**: Store up to 3 contacts
- **Vibration & Sound**: Multi-sensory emergency feedback
- **Popup Modal**: Visual confirmation with contact list

### 👤 Profile Management
- Profile picture upload (localStorage)
- Name and email fields
- 3 emergency contacts
- Edit/Save mode for contact management
- Ring connectivity with animation

### 📚 Safety Tips
- 6 educational safety tip cards
- Topics: lighting, location sharing, confidence, instincts, contacts, connection
- Staggered entrance animations

### 🕓 Walk History
- View past walk sessions
- Date, route, and duration tracking
- Click to center map on location
- Stores last 10 walks

### 🔐 Authentication
- Login/Signup modal with mode switching
- LocalStorage-based (demo)
- Backdrop blur effect

## 🎨 Design System

**Colors:**
- Background: Isabelline `#F3F3E3`
- Text: Feldgrau `#606F69`
- Accents: Light Blue `#A7C7E7`
- SOS: Red `#ff5b5b`
- Success: Green `#26c281`

**Animations:**
- Page transitions (fade-in, slide-up)
- Button micro-interactions (hover, glow)
- Card entrance animations (staggered)
- SOS button pulse
- Ring connection animation

## 🚀 Quick Start

### Simple Usage (No Installation)
1. Download `index.html` and `ICON.jpg`
2. Place both files in the same folder
3. Double-click `index.html`
4. Open in any modern browser

### Local Server (Recommended)
```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

## 📱 Browser Support

- ✅ Chrome (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Requires internet for map tiles and geocoding

## 🔧 Technical Stack

- **Pure HTML/CSS/JS** - No frameworks
- **Leaflet.js 1.9.4** - Interactive maps
- **Font Awesome 6.4.0** - Icons
- **OpenStreetMap** - Map tiles (CARTO Light)
- **Nominatim API** - Geocoding (India-focused)
- **OSRM API** - Walking route calculation

## 💾 Data Storage

All data stored in browser's **localStorage**:
- `walkmate_user_name` - User name
- `walkmate_user_email` - User email
- `walkmate_profile_pic` - Base64 profile image
- `safewalk_ec1`, `safewalk_ec2`, `safewalk_ec3` - Emergency contacts
- `walkmate_ring_connected` - Ring connection state
- `safewalk_history` - Walk history (max 10 entries)

## 📐 Architecture

**Single-page application:**
- All styles inline (CSS)
- All logic inline (JavaScript)
- External CDN dependencies only
- No build process required
- File size: ~44KB

## 🎯 Use Cases

- Night walk safety tracking
- Emergency contact alerts
- Community safety companion
- Educational safety tips
- Walk history logging
- Future hardware integration (ring connectivity)

## 🔒 Security Note

This is a **demonstration/prototype application**:
- ❌ No real authentication
- ❌ No backend server
- ❌ No actual SMS/notification sending
- ✅ Educational and pitch purposes only
- ✅ All data stays in browser (localStorage)

## 📱 Responsive Design

- **Mobile** (<768px): Stacked layout, full-width buttons
- **Tablet** (768-1024px): Optimized spacing
- **Desktop** (>1024px): Full feature display
- Touch-friendly targets (44px minimum)

## 🎥 Demo Flow

1. **Home Page** - Set route (Hyderabad landmarks)
2. **Start Walk** - Live timer + GPS simulation
3. **SOS Button** - Emergency modal with contacts
4. **Profile** - Upload photo, set 3 contacts
5. **Safety Tips** - Educational content
6. **History** - View past walks

## 📄 License

This is a prototype application for demonstration purposes.

## 🤝 Contributing

This is a completed prototype. For improvements or questions, please open an issue.

---

**Built with ❤️ for safer night walks**
