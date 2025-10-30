# 🚗 Vehicle Movement Simulator

A simple and interactive **Vehicle Movement Simulator** built using **Leaflet.js**, **HTML**, **CSS**, and **JavaScript**.  
This web app visualizes a simulated vehicle moving along a route in **Hyderabad, India**, showing live position, speed, and distance in real time.

---

### 🌍 Features

- 🗺️ **Live Map Tracking:** Displays a moving vehicle on an interactive map.  
- ⚡ **Dynamic Data:** Calculates and updates speed, total distance, and progress.  
- 🎮 **Simulation Controls:**
  - ▶ **Play** — Start the simulation  
  - ⏸ **Pause** — Temporarily stop  
  - ⏹ **Reset** — Restart from the beginning  
- ⏩ **Speed Adjustment:** Change playback speed (1x–10x).  
- 📊 **Progress Bar:** Visual route completion indicator.  
- 💬 **Popup Info:** Shows vehicle ID, current status, and last update time.  
- 📱 **Responsive Design:** Optimized for desktop and mobile screens.

---

### 🧠 Tech Stack

- **HTML5** — Structure  
- **CSS3** — Styling and layout  
- **JavaScript (Vanilla)** — Logic and animation  
- **Leaflet.js** — Map rendering  
- **OpenStreetMap** — Map data provider

---

### 🛠️ How to Run Locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/vehicle-movement-simulator.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd vehicle-movement-simulator
   ```

3. **Run the app:**
   - Open `index.html` in any modern web browser.  
   - No additional setup or dependencies required.

---

### 📂 Folder Structure

```
vehicle-movement-simulator/
│
├── index.html          # Main application file
├── README.md           # Project documentation
└── assets/             # (Optional) Static assets or data files
```

---

### ⚙️ Simulation Details

The simulator uses static JSON data (`dummyRouteData`) representing 20 coordinates in Hyderabad, India.  
Each point includes:
```js
{
  latitude: 17.385044,
  longitude: 78.486671,
  timestamp: "2024-07-20T10:00:00Z"
}
```
The script calculates speed and total distance dynamically using these coordinates.

---

### 🚀 Future Improvements

- Add **real-time GPS API** integration.  
- Support for **multiple vehicles**.  
- Include **charts** (speed vs. time, distance, etc.).  
- Allow **data export** (CSV/JSON).  
- Add **dark mode** for UI.

---

### 👨‍💻 Developer

**Built by Sathishkumar**  
Powered by **Leaflet.js** & **OpenStreetMap**  
© 2025 — Vehicle Movement Simulator
