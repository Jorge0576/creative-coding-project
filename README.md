# Creative Coding Practices

## Description
An interactive p5.js sketch that visualizes live weather data as a dynamic particle system. I built a swarm of 3,000 particles whose color, transparency, size, speed, and flow all respond in real time to temperature, cloud cover, UV index, wind speed, and wind direction from the Weatherstack API.

## Files
- `index.html` – Hosts the sketch  
- `sketch.js` – Initializes particles, fetches weather data, and maps weather metrics to visual and motion parameters  
- `p5.min.js` – p5.js library  

## Usage

1. Clone this repo.  
2. In VS Code, install the **Live Server** extension (by Ritwick Dey).  
3. Right‑click `index.html` → **Open with Live Server**.  
4. Your default browser will open the sketch.  
5. When prompted, enter a latitude and longitude to fetch live weather data—watch the particles respond in real time.

## St. Thomas Convictions
- **Personal Attention**  
- **Diversity**  

## Highlights
- Mapped five weather parameters to five visual dimensions (hue, alpha, stroke weight, speed, angle) for a multi‑sensory experience.  
- Employed Perlin noise and vector math to create organic, swirling motion influenced by real‐world data.
