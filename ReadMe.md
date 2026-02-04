![ElectronicsHub](GridCOM.jpg)

# ElectronicsHub: Egypt Component Search & Compare
ElectronicsHub is a specialized web dashboard built for the **Egyptian electronics community**. It streamlines the process of sourcing components by aggregating search results from the most popular electronics retailers in Egypt into a single, high-density interface.

## 🇪🇬 Supported Egyptian Stores
The tool is pre-configured to search the following local providers:

* **Retail Giants:** Ram E-Shop, Makers Electronics, and Fut Electronics.
* **Specialized Hubs:** Lampatronics, UGE One, and MicroOhm.
* **3D Printing & CNC:** IN3D Shop, 3DSmart Shop, and CNC Egypt.
* **Niche & Hobbyist:** Free Electronic, Circuits Elec, DIY Electronics, Ampere Electronics, Op-Tronic, Electra store, and Dev Boards.
* **Official Channels:** Raspberry Pi (Egypt Distribution).

---

## 🚀 Key Features

* **Unified Search:** Query all 18+ Egyptian stores simultaneously with one search term.
* **High-Density Grid:** A scannable layout designed to quickly spot stock availability across different vendors.
* **Comparison Mode:** Load up to 6 stores side-by-side in real-time to compare prices and shipping rates without leaving the app.
* **PCB Aesthetic:** A professional dark-themed UI inspired by JetBrains Mono and modern engineering tools.

---

## ⚠️ Important: Iframe Connectivity (Refused to Connect)

Because this tool loads external websites into frames for comparison, you may encounter a **"refused to connect"** error on certain sites (notably **Lampatronics** and **Raspberry Pi**).

### Why this happens:
Many Egyptian websites implement a security header called `X-Frame-Options: SAMEORIGIN`. This is a security measure that prevents their site from being "framed" by other domains to protect against clickjacking.

### How to resolve:
1.  **Visit Directly:** Every card includes a **"Visit"** button. Clicking this will open the search result in a new tab, bypassing the restriction.
2.  **Browser Extensions:** For power users or personal use, you can install a browser extension like **"Ignore X-Frame-Options"** (available for Chrome and Edge). This will allow the sites to load perfectly within the dashboard's comparison panes.

---

## 🛠️ Getting Started

This is a standalone, client-side React application. No installation or server-side setup is required.

1.  Clone or download this repository.
2.  Open `index.html` in any modern web browser.
3.  Enter a part name (e.g., "LM317" or "Arduino Nano") and start comparing local prices instantly.

---

*Built for the makers, engineers, and students of Egypt.*