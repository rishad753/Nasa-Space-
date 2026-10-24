<<<<<<< HEAD
# # Project NEXUS-FRONTIER (SPARK-FRONTIER) 🚀
> **NASA Space Apps Challenge 2026** | **Location:** Mymensingh, Bangladesh (Local In-Person Event)  
> **Challenge Target:** CLPS Lunar Mission Browser / Space Exploration  
> **Developed by:** Team Sparks  
> **Status:** 🛠️ Active Alpha Development & Live Prototyping

---

## 🎬 OFFICIAL GAMEPLAY WALKTHROUGH VIDEO
👉 **[CLICK HERE TO WATCH OUR 4-MINUTE PROJECT DEMO VIDEO](https://youtu.be/2tlQw88tB0k?si=aH3N1Aa65kRewZky)** 🌌

---

## 🌌 The Inspirational Vision
> *"In the dark, a spark is born —*
> *A child's wonder, quiet, warm.*
> *They look up at the endless sky,*
> *And ask the question: 'Can I fly?'*
> *We are Team SPARKS — we heard the call,*
> *We built a bridge for one and all."*

Project **NEXUS-FRONTIER** is a high-fidelity, browser-based 3D Space Survival and Exploration Simulation Game explicitly engineered to ignite scientific curiosity in children aged 8 to 15. It bridges the gap between raw aerospace telemetry and gamified visual education by directly transforming complex lunar and planetary surface metrics into an interactive, high-performance web sandbox campaign with zero client-side installation required.

---

## 📡 Core NASA Open Resources Integration
Our dynamic simulation engine directly injects real-world aerospace parameters from 5 official NASA open-source datasets and APIs to run its internal physics, asset shaders, and audio frameworks:

1. **NASA Exoplanet Archive TAP API:** Deployed inside `src/store/gameStore.js` via the `fetchPlanetData` module. It queries the `pscomppars` table using ADQL to extract raw `pl_name`, `pl_masse`, `pl_eqt`, and `pl_insol` fields. These metrics dynamically calculate gravity constants, ambient temperature parameters, and solar array kilowatt outputs.
2. **NASA Mars Rover Photos API:** Fetches geological and topographical distributions from active Curiosity and Perseverance rover endpoints. This data directly shapes the high-fidelity texturing of our 3D isometric surface terrains.
3. **NASA Image and Video Library API:** Integrated into our onboarding assets layer to execute direct asset queries, constructing the immersive environment loops for our cinematic landing dashboard.
4. **NASA SoundCloud (Space Sounds Library):** Deployed using the Howler.js framework to integrate authentic audio logs, signal hums, and radio frequency samples into our real-time crisis audio tracks.
5. **NASA 3D Resources:** Imports official planetary texture maps (`mars.jpg`, `moon.jpg`) mapped using Three.js `TextureLoader` to render highly detailed 3D astronomical spheres.

---

## 🛠️ Technical Stack & Architecture
- **Frontend Architecture:** React.js (Vite Core Optimization)
- **3D Render Pipeline:** React Three Fiber (R3F) & Three.js (WebGL Component Shaders)
- **State Management Engine:** Zustand (High-performance reactive global store)
- **Styling & UI Animation:** Tailwind CSS + Framer Motion Elements
- **Audio Architecture:** Howler.js (Data-driven cosmic frequency tuning)

---

## 🏗️ Core Application Modules & Gameplay Loops

### 1. Live HUD Dashboard & 3D Isometric Crafting
Players take control of a 3D astronaut exploring the reactive surface terrain. The top-left HUD actively tracks 5 core life-support attributes: **Health, Oxygen, Power, Temperature, and Radiation**. Players must strategically spend their initial budget to deploy survival structures:
- **Oxygen Domes:** Prevents critical life-support depletion vectors.
- **Solar Arrays:** Generates local kilowatt grid power based on insolation data.
- **Thermal Regulators & Shields:** Mitigates extreme environmental constraints.

### 2. Tactical Cosmic Disasters (The Crises Engine)
To drive active exploration and penalize static exploits, moving across the terrain triggers random environmental anomalies. As night falls, a sudden **Electrostatic Moon-Dust Storm** or **Solar Flare** alert strikes. If defensive shields are not deployed immediately, the base faces instant mission termination ("BLOWN AWAY").

### 3. NEXA's Quiz & Core Educational Benefit
Upon tracking down and reaching the damaged deep space communication tower, a strict economic constraint triggers: *NOT ENOUGH MONEY* to craft the missing Antenna Dish. This is where our primary educational impact happens. To earn space credits, children must open **NEXA's Quiz**. This module tests them on space facts and planetary metrics that were displayed earlier as subtle floating information overlays during surface exploration, rewarding active memory retention and data analysis.

### 4. Client-Side Vector Certificate Exporter
Answering correctly grants an immediate space credit boost of **\$10,000**, used to craft the final components. Once the tower is repaired, a brilliant blue transmission beam connects the colony with Earth. The system compiles the final global parameters to generate a downloadable, personalized **Certified Space Colonist** banner.

---

## 🚀 How to Run Locally

### Prerequisites
Ensure you have **Node.js** (v18 or higher) installed on your system.

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com
   ```
2. Navigate into the project directory:
   ```bash
   cd nexus-frontier
   ```
3. Install the optimized dependencies:
   ```bash
   npm install
   ```
4. Start the local development server:
   ```bash
   npm run dev
   ```
5. Open your browser and navigate to `http://localhost:5173`

---

## 🚧 Current Roadmap & Future Updates
- **📱 Responsive Mobile Cross-Platform Version:** We are actively compiling our React Three Fiber bundle into a native wrapper (Capacitor/React Native) to launch SPARK-FRONTIER natively on iOS and Android handheld screens very soon.
- **🤖 Automated AI Voice Mentors:** Setting up native DeepSeek API voice modules inside our virtual mascot helper bot NEXA.
- 
=======
# Nasa-Space-
>>>>>>> 1c1e032610ab4ab7de3406f97bba965dfb36739a
