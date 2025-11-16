# SmartEnergy Alert – Youth-Created Prototype (EduHack Adjud 2025)

**SmartEnergy Alert** is an educational web prototype (with a future mobile app vision) created by young people during **EduHack Adjud 2025 – Digital Skills for Equal Futures**, in Adjud, Vrancea, Romania.

The app helps citizens understand **when electricity is cheaper, normal or expensive** during the day and encourages smarter, more sustainable energy use at home.

🌐 **Live demo:** https://appsmartenergyalert.netlify.app/  
🇬🇧 / 🇷🇴 **Bilingual interface:** English & Romanian (language switch in the header)

---

## 🎯 Concept & Goals

- Turn a **real local problem** (high and fluctuating energy prices) into a **digital solution** designed by youth.
- Help families (especially those with low/medium income) see **when it is a good moment to use high-consumption devices**.
- Offer an **intuitive interface** that can be used in schools, community centres and households as an **educational tool**.
- Show that **young people can read data, understand it and turn it into a useful app** for their city.

> For now, the demo uses a **simulated price curve** for educational purposes. In the future, it can be connected to real energy price APIs.

---

## ✨ Main Features

### 1. Interactive Energy Mood Demo
- Slider for **selecting any hour of the day (0–23)**.
- For each selected hour, the app shows:
  - `Cheap energy` / `Normal price` / `Expensive energy`
  - Estimated price (lei/kWh – simulated)
  - A short, clear **recommendation** for using appliances.
- When the price enters an **expensive (red) zone**, the user sees a **push-style notification (toast)** – a first step towards a real mobile alert.

### 2. Simple Cost Planner (Hour X to Hour Y)
- Select **Start hour** and **End hour** for an appliance (e.g., washing machine).
- The app calculates:
  - **Average price** on the selected interval.
  - **Estimated cost** for a sample consumption (e.g., 2 kWh).
- Offers **advice**:
  - Green (cheap) interval – good for heavy appliances.
  - Yellow (normal) – OK, but could be optimized.
  - Red (expensive) – better to avoid if possible.

### 3. Bilingual Interface (EN / RO)
- Language switcher (flags) in the header:
  - 🇬🇧 English
  - 🇷🇴 Română
- All UI texts (sections, labels, tooltips, messages, toast) change **instantly** without reloading the page.

### 4. Story of the Project
- Sections explaining:
  - Why the idea matters for the local community.
  - How young people from **Adjud and EU countries** designed the prototype.
  - What skills they developed: digital skills, data literacy, teamwork, communication, energy awareness.

### 5. Educational, Not Just Technical
- The page is designed as a **learning resource**:
  - For **youth**: experimenting with data, logic, UX and communication.
  - For **teachers & mentors**: a concrete example of a DigiEduHack outcome.
  - For **communities**: a starting point for local energy awareness actions.

---

## 👩‍💻👨‍💻 Who Created It?

The prototype was created during **EduHack Adjud 2025 – Digital Skills for Equal Futures** by:

- **33 young people**:
  - 21 participants from **Adjud & Vrancea, Romania**
  - 12 participants from **several EU countries** (online)
- Roles taken by youth teams:
  - Problem mapping: collecting real stories about energy bills and home habits.
  - Data & logic: defining simple rules for cheap/normal/expensive hours.
  - UX & interface: designing screens that are easy to understand.
  - Testing & feedback: checking clarity with peers and adults.
  - Storytelling: explaining why the app matters.
- Educators & mentors facilitated, guided and ensured **inclusion & local relevance**.

---

## 🧡 Support & Context

This educational prototype was developed in Adjud within activities supported by:

- **Fundația Orange România**
- **Orange Digital Center**
- Local partners and schools in Vrancea

The project aligns with the **DigiEduHack** vision:  
using digital skills and creativity to solve **real educational and societal challenges**.

---

## 🛠️ Tech Stack

- **Pure HTML + CSS + Vanilla JavaScript**
- No external frameworks required
- Runs entirely in the **browser** (front-end only)

---

## 🚀 How to Run Locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox, etc.).
3. No build step, no backend – it is a **static front-end prototype**.

Optionally, you can host it using:
- Netlify
- GitHub Pages
- Any static hosting provider

---

## 🧠 How the Simulation Works

The app uses a **simple simulated price curve** for a typical day:

- Night (0–6): cheaper energy  
- Morning (6–9): more expensive (peak)  
- Midday (9–13): medium  
- Early afternoon (13–17): cheaper again  
- Evening (17–22): most expensive peak  
- Late evening (22–24): medium

For each hour:
- A function `getPriceForHour(hour)` returns a price in **lei/kWh**.
- Based on thresholds, hours are classified into:
  - **Green** – cheap
  - **Yellow** – normal
  - **Red** – expensive
- This drives both:
  - The **live demo** (slider + recommendation + status)
  - The **interval planner** (average price + cost + advice)

In future versions, this logic can be replaced by:
- Real-time data from energy markets or grid operators.
- APIs from energy providers.
- Different curves for different user profiles.

---

## 🧩 Possible Future Developments

- 📱 Turn the prototype into a **real mobile app** (e.g., PWA or native).
- 🔗 Connect to **real-time energy price APIs**.
- 👤 Add profiles for different types of users (small families, larger households, elderly, etc.).
- 🔔 Implement **real push notifications** on mobile.
- 📊 Add graphs with **daily / weekly stats** about energy use.
- 🌍 Adapt the solution for other cities and countries in the EU.

---

## 🌱 Educational Use

SmartEnergy Alert can be used in:

- **Hackathons & innovation labs** – as a model challenge & prototype.
- **School projects** – to teach digital skills, energy literacy and critical thinking.
- **Community workshops** – to start discussions about **energy poverty** and solutions.

---

## 📝 License & Credits

- This prototype was created in an **educational context** during **EduHack Adjud 2025**.  
- The content and idea can be reused and adapted for **non-commercial educational purposes**, mentioning:
  - **EduHack Adjud 2025 – Digital Skills for Equal Futures**
  - **Asociația Grupul Verde** (Adjud, Vrancea, Romania)
  - **Fundația Orange România & Orange Digital Center** (support)

For collaborations, partnerships or further development, please contact:  
**Marian Dumitru – Project Manager, Asociația Grupul Verde**  
Adjud, Vrancea, Romania

---
## 🇷🇴 Rezumat pe scurt (în limba română)

**SmartEnergy Alert** este un prototip educațional de aplicație web, creat de tineri în cadrul **EduHack Adjud 2025 – Digital Skills for Equal Futures**, care îi ajută pe locuitori să vadă când energia este ieftină, normală sau scumpă și să își planifice consumul mai inteligent.

- Demo activ: slider pe ore, recomandări, notificare de tip „push”.
- Planificator simplu: estimează costul între ora X și ora Y.
- Interfață **bilingvă EN/RO**.
- Creat de **33 de tineri** (Adjud & UE), cu sprijinul **Fundației Orange România** și **Orange Digital Center**.
- Proiect gândit pentru **educație, comunitate și viitoare dezvoltări reale** (date reale, aplicație mobilă, extindere europeană).

---
