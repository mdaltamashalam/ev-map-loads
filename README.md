# ⚡ EV Charger Locator - Delhi & All India

A smart EV charger locator web app that allows users to **search routes**, **scan for electric vehicle chargers**, and **visualize charger locations** dynamically using **Mapbox GL JS** and the **Open Charge Map API**. Designed for **Delhi** and **all-India coverage**, this project emphasizes real-world deployment with smooth animations, mobile responsiveness, and premium UI/UX.

---

## Demo - Please Open in Laptop for Clear View of Hosted Project.

🔗 [Live Demo (Optional if hosted)](http://ev-map-loads.s3-website-us-east-1.amazonaws.com/)

---

## Project Purpose

As electric vehicles grow across India, charger availability and discoverability become critical. This project solves that by:

- Helping EV drivers **scan and locate chargers** directly along a planned route.
- Providing a **visually interactive map-based interface**.
- Supporting **both Delhi-specific and pan-India exploration**.

---

## 🛠 Tech Stack

| Layer           | Technology                                   | Purpose                                      |
|----------------|----------------------------------------------|----------------------------------------------|
| 🗺️ Frontend     | HTML, CSS, JavaScript                        | Responsive UI, charger visualization         |
| 📍 Maps         | Mapbox GL JS, Mapbox Directions API          | Map rendering, geocoding, route planning     |
| 🔌 API          | Open Charge Map API                          | Charger data retrieval                       |
| 🎨 UI Design    | Custom CSS (Media Queries)                   | Mobile-first design, controls, popups        |
| ⚙️ Hosting      | GitHub Pages / Local                         | Lightweight frontend deployment              |

---

## ✨ Features

- 🚗 **Input Start & End Points** via Geocoder
- 🗺️ **Route Visualization** using Mapbox
- ⚡ **Dynamic Scan** of nearby EV chargers within 5km radius along route
- 📍 **Interactive Marker Popups** showing charger title, address, type, and power
- 💡 **Smart Animation** to simulate scanning and plotting
- 📱 **Fully Responsive** for mobile and desktop

---

## 🔧 How it Works

1. **User selects start and end location** using the Mapbox Geocoder.
2. The app fetches a **route** via Mapbox Directions API.
3. It **interpolates the route** into ~1km segments.
4. For each point:
   - It queries Open Charge Map for **chargers within 5km**.
   - Unique charger markers are added to the map with details.
5. The UI shows **scan progress** and **total chargers found**.

---

## 🔑 API Keys Used

| API               | Description                     |
|------------------|---------------------------------|
| Mapbox Access     | Map rendering, geocoding, routes |
| OpenChargeMap     | EV charger data (OCM Key)        |

---

## 🧭 Supported Locations

- ✅ **Delhi NCR**
- 🌐 **All India Compatible**

The app uses latitude/longitude and does **not limit to city boundaries**, making it scalable across India.

---

## ✅ Actions Taken

| Step | Task |
|------|------|
| 1️⃣  | Designed UI layout & responsiveness from scratch |
| 2️⃣  | Integrated Mapbox GL JS with route drawing       |
| 3️⃣  | Connected Open Charge Map API for real-time data |
| 4️⃣  | Built animation logic for route-based charger detection |
| 5️⃣  | Optimized UX for mobile and desktop               |

---

## 🧩 Challenges Solved

- Smooth real-time animation of route scans.
- Filtering duplicate charger results on overlapping segments.
- Balancing design for performance on lower-end devices.

---

## 📷 Screenshots

| Home Page | Route Scan Example |
|-----------|--------------------|


<img width="1920" height="951" alt="14 07 2025_23 50 11_REC" src="https://github.com/user-attachments/assets/9943b250-7f29-46a4-b48d-b9cbde698998" />

---

## 🌍 Future Enhancements

- ⚙️ Backend integration with Node.js + MySQL (custom EV data)
- 🧠 AI/ML-based charger recommendation
- 🧾 Filter by charger type, provider, power, availability
- 📈 Analytics dashboard for charger usage

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

---

## License & Copyright

© 2025 Vintara Project Team. All rights reserved.

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

You are free to use, modify, and distribute this software under the terms of the MIT License. However, please give appropriate credit to the original authors and do not use this project for unlawful or unethical purposes.

---

**Note:**  
- Redistribution of this code or any derived work must include this copyright notice.  
- Commercial use is allowed under the license, but attribution is required.  
- No warranty is provided. Use at your own risk.

For any questions about licensing, please contact the project maintainers.

---

## 🙌 Made with ❤️ by [Md Altamash Alam](https://github.com/mdaltamashalam)
