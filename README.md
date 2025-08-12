<p align="center">
  <img src="https://raw.githubusercontent.com/Gargi016/MUJ-Uniway/main/muj%20naviagation%20.jpg" alt="MUJ UniWay Project Banner">
</p>

<h1 align="center">MUJ UniWay</h1>

<p align="center">
  <i>Your Interactive Campus Navigation Assistant</i>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
    <img src="https://img.shields.io/badge/Leaflet-1EB300?style=for-the-badge&logo=leaflet&logoColor=white" alt="Leaflet.js">
</p>

<p align="center">
  <a href="#-live-demo">Live Demo</a> •
  <a href="#-our-journey">Our Journey</a> •
  <a href="#-key-features">Key Features</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-results">Results</a> •
  <a href="#-future-roadmap">Future Roadmap</a>
</p>

---

## 🚀 Live Demo

[![GitHub Pages Deploy](https://img.shields.io/badge/View_Live_Demo-222222?style=for-the-badge&logo=github&logoColor=white)](https://gargi016.github.io/MUJ-Uniway/)

**Click the badge above or follow this link to try the live application:** [https://gargi016.github.io/MUJ-Uniway/](https://gargi016.github.io/MUJ-Uniway/)

This application is a lightweight, static web app deployed via GitHub Pages, ensuring fast load times and universal accessibility.

---

## 📖 Project Overview

[cite_start]Navigating the expansive Manipal University Jaipur (MUJ) campus poses a significant challenge for new students, visitors, and even faculty[cite: 5]. [cite_start]**MUJ UniWay** is an interactive, web-based campus navigation platform built to solve this problem[cite: 16]. [cite_start]By providing a feature-rich, easy-to-use digital map, our project eliminates the frustration of finding specific destinations and enhances the overall campus experience for the entire university community[cite: 8]. [cite_start]This solution directly addresses the lack of a comprehensive digital tool for real-time navigation at MUJ[cite: 7].

---

## 🗺️ Our Journey: From a Simple Map to a Smart Navigator

This project was built iteratively, with each phase designed to solve a core challenge of on-campus navigation.

<details>
<summary><strong>Phase 1: The Standard Map - An Imperfect Start</strong></summary>
<br>
Our initial prototype successfully rendered an interactive map of MUJ using Leaflet.js, displaying key buildings and locations. However, when we implemented a standard routing engine, it treated the campus like a public space, generating incorrect routes that ignored footpaths and internal roads.
<br><br>
💡 **Lesson Learned:** Standard routing tools are insufficient for private, complex environments like a university campus. A custom data-driven approach is necessary.
</details>

<details>
<summary><strong>Phase 2: The Smart Navigator - The Final, Robust Solution</strong></summary>
<br>
To solve the routing problem, we manually mapped the campus's true pathways—footpaths, service roads, and shortcuts—into a custom GeoJSON dataset. This allowed us to build a "Smart Path" system.
<ul>
  <li><strong>Accurate Custom Paths:</strong> The map now displays the actual, walkable routes inside the campus, providing navigation guidance that is far more accurate than any public mapping service.</li>
  <li><strong>Instant Search & Highlighting:</strong> We added a live search that not only flies to the location but also places a distinct pointer on the exact building, providing immediate visual confirmation for the user.</li>
    <li><strong>Dynamic Filtering & Info:</strong> Users can now filter locations by category (e.g., Academic, Dining) and view real-time information like operating hours, making the map a truly useful daily tool.</li>
</ul>
<br>
✅ **The Result:** A reliable and intelligent navigation assistant that solves the core problem of getting around the MUJ campus efficiently.
</details>

---

## ✨ Key Features

- [cite_start]**Interactive Campus Map**: A high-performance, interactive map of the entire MUJ campus with detailed building outlines and location markers[cite: 21].
- [cite_start]**Live Search with Pointer**: Instantly search for any building by name; the map not only centers on the location but adds a special pointer for easy identification[cite: 22].
- **Accurate On-Campus Paths**: Displays all major footpaths and roads, providing a true representation of how to navigate within the campus.
- [cite_start]**Dynamic Category Filtering**: Filter locations by categories like "Academic," "Dining," and "Sports" to explore the campus thematically[cite: 24].
- [cite_start]**Real-time Information**: Click on any location to see its current status and operating hours in a clean, accessible info panel[cite: 25].
- [cite_start]**"Route from My Location"**: Instantly create a route from your current GPS location to any point on campus[cite: 23].

---

## 🛠️ Tech Stack

| HTML5 | Tailwind CSS | JavaScript | Leaflet.js |
| :---: | :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/Ritviks21/Silicon-Sentinel/main/docs/images/html.png" width="48"> | <img src="https://raw.githubusercontent.com/Ritviks21/Silicon-Sentinel/main/docs/images/tailwind.png" width="48"> | <img src="https://raw.githubusercontent.com/Ritviks21/Silicon-Sentinel/main/docs/images/js.png" width="48"> | <img src="https://raw.githubusercontent.com/Ritviks21/Silicon-Sentinel/main/docs/images/leaflet.png" width="48"> |

---

## 📊 Results & Evaluation

Our application provides a clean, intuitive, and highly functional solution to the campus navigation problem. The screenshots below demonstrate key features in action.

<p align="center">
  <b>Complete Campus View with Custom Paths</b><br><br>
  <img src="https://raw.githubusercontent.com/Gargi016/MUJ-Uniway/main/muj%20naviagation%20.jpg" alt="A screenshot showing the complete campus map with buildings and paths." width="600">
</p>

<p align="center">
  <b>Live Search with Pointer and Info Panel</b><br><br>
  <img src="https://raw.githubusercontent.com/Gargi016/MUJ-Uniway/main/sc%202.jpg" alt="A screenshot showing the search pointer on a building with the info panel open." width="600">
</p>

---

## 🚀 Getting Started

This is a static web project and requires no complex installation.

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/Gargi016/MUJ-Uniway.git](https://github.com/Gargi016/MUJ-Uniway.git)
    cd MUJ-Uniway
    ```

2.  **Run Locally**
    Simply open the `index.html` file in any modern web browser.

---

## 🔮 Future Roadmap

[cite_start]This project has significant potential for future growth[cite: 53]. Our implementation roadmap includes:
- **Guided Campus Tours**: Pre-defined walking tours ("Campus Highlights," "First-Year Essentials") for visitors and new students.
- **Augmented Reality Viewfinder**: An AR mode to overlay location information directly onto the live camera feed.
- **Class Schedule Integration**: Allowing students to connect their schedule for quick routing to their next class.
- **Indoor Mapping**: Extending the map to navigate inside complex buildings like the library and academic blocks.

---

## 🤝 The Team: DOT

This project was developed by:

- **Gargi Das**: [GitHub](https://github.com/Gargi016) | [LinkedIn](https://www.linkedin.com/in/gargi-das-0026b331a/)
- **Ritvik Raj Singh**: [GitHub](https://github.com/Ritviks21) | [LinkedIn](https://www.linkedin.com/in/ritvik-raj-singh-429922379?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
