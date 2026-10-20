# 🚑 Klinik Dr. Prevents — Control Centre Patient Dispatch System

An interactive, single-page web application designed for the Control Centre department of **Klinik Dr. Prevents** to quickly locate nearby branches, check facility availability (such as 24-hour service & X-Ray), and dispatch patients with automated navigation links via WhatsApp.

---

## 🌟 Key Features

* 📍 **Interactive Klang Valley Map**: Built with Leaflet.js and OpenStreetMap for real-time visual tracking of all 10 branches across Kuala Lumpur and Selangor.
* 🔎 **Accurate Area Geocoding**: Search by *Taman*, *Lorong*, *Jalan*, or postal code with optimized Klang Valley bounds.
* 🩻 **X-Ray Filter Mode**: Instantly filter and re-rank branches that have active X-Ray facilities:
  * **X-Ray Available**: Kepong, Segambut, Jalan Ipoh, Bandar Sri Damansara.
  * **24 Hours Available**: All branches.
* 📏 **Haversine Distance Calculation**: Automatically calculates straight-line and driving proximity from any queried point to every branch in kilometers.
* 📲 **Direct Patient Dispatch**: Generate pre-formatted WhatsApp dispatch messages containing the exact Google Maps navigation link, address, and hotline contact (`0168485911`).
* ➕ **Dynamic Branch Manager**: Add, edit, or delete custom branches directly from the interface with built-in address geocoding and `localStorage` persistence.

---

## 🏥 Covered Clinic Locations

### Kuala Lumpur Branches
1. **Klinik Dr.Prevents Kepong 24 Jam** (X-Ray ✅)
2. **Klinik Dr.Prevents Segambut 24 Jam** (X-Ray ✅)
3. **Klinik Dr.Prevents Jalan Ipoh 24 Jam** (X-Ray ✅)
4. **Klinik Dr.Prevents Bandar Sri Damansara 24 Jam** (X-Ray ✅)

### Selangor Branches
5. **Klinik Dr.Prevents Damansara Jaya 24 Jam**
6. **Klinik Dr.Prevents 24 JAM Pj Old Town**
7. **Klinik Dr.Prevents SS15 24 Jam**
8. **Klinik Dr.Prevents 24 JAM Taipan Business Centre**
9. **Klinik Dr.Prevents Bandar Puteri Puchong 24 Jam**
10. **Klinik Dr. Prevents Kota Kemuning 24 Jam**

---

## 🚀 How to Run / Deploy

### Host on GitHub Pages
1. Push `index.html` to the `main` branch of your GitHub repository.
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch** and select `main`.
4. Your application will be live instantly!

---

## 📞 Support & Emergency Hotline
* **Control Centre Hotline**: `0168485911`
