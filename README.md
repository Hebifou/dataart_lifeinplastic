# Life in Plastic – Data Art Projection (2020–2090)

**A data-driven art project visualizing the projected growth of oceanic plastic pollution under a “business-as-usual” scenario.**

This notebook combines environmental data, scientific projections (NOAA, WWF, Ellen MacArthur Foundation) and minimalist design to create an animated visualization of how plastic waste may accumulate across the world’s oceans.  
Each glowing ring represents a *major ocean gyre* where plastic concentrates — expanding gradually over time to symbolize linear growth in global plastic output.

---

## Visualization

### Modeled Projection (GIF)
![Life in Plastic – Projection](reports/plastic_pollution_animation.gif)

---

## Concept

- **Goal:** Turn raw quantitative data into an emotionally resonant data art piece.  
- **Model:** Linear extrapolation of plastic production growth, approx. +12 M tons per year (2020–2090).  
- **Focus:** Great Pacific, North Atlantic, South Pacific, and Indian Ocean gyres.  
- **Design:** Minimal dark-map style, glowing red-yellow highlights, and smooth radial animation.

---

## Tech Stack

- **Python** · Matplotlib · Cartopy · Pillow · NumPy  
- **Animation:** `matplotlib.animation.FuncAnimation`  
- **Export formats:** `.mp4` (via ffmpeg) and `.gif` (via Pillow)

---

## Data Sources

- **NOAA (2020–2025)** — Global marine debris and ocean plastic estimates.  
- **WWF (2021)** — *Plastic in the Ocean* report.  
- **Ellen MacArthur Foundation (2021)** — *Circular Economy of Plastics*.  
- **Walmart ESG Report (2020)** — Corporate plastic packaging footprint.

---

## Author

**Modeling & Visualization:** [Hiba Fouani](https://github.com/Hebifou)  
*Made with Python, purpose, and a touch of data art.*

---

## License

This project is released under the [MIT License](LICENSE).  

---
