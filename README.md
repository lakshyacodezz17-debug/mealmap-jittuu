# 🥗 MealMap Campus

> **Centralized Campus Food Outlets, Live Menus, Real-Time Availability, Ingredient Transparency & Allergen Safety Platform.**

MealMap solves the daily campus dilemma: students rushing across campus only to find long lines, closed kitchens, sold-out meals, or undisclosed allergens. With MealMap, students can explore real-time menus across every dining hall and cafe, filter by dietary requirements, calculate nutrition, and plan meals safely.

---

## 🌟 Key Features

- **🍽️ Centralized Multi-Outlet Directory**:
  - Live status for all campus food outlets (open/closed, opening hours, building & floor location).
  - Real-time crowd barometer (Low, Moderate, Busy, Very Busy) with estimated line wait times.
  - Accepted payment badges (Meal Swipes, Student ID card, Cash/UPI).

- **⚡ Real-Time Food Availability**:
  - Live stock indicators: `In Stock` (with portion count), `Few Left`, `Sold Out`, and `Coming Soon`.
  - Notification alerts for when sold-out items return to stock.

- **🛡️ Ingredient Transparency & Allergen Safety Guard**:
  - Full ingredient disclosure for every menu item.
  - Personal student safety profile (Peanuts, Tree Nuts, Dairy, Gluten, Soy, Eggs, Shellfish, etc.).
  - Automatic, high-visibility allergen warnings (`⚠️ Warning: Contains Dairy & Gluten`) on dishes and trays.

- **🌿 Comprehensive Dietary Classification**:
  - Filter across Vegetarian, 100% Vegan, Halal Certified, Gluten-Free, High-Protein, Jain-Friendly, Nut-Free, and Keto.
  - Quick budget filter: **Under $5 Meals**.

- **📊 Nutritional Facts Sheet**:
  - Accurate macro breakdown per dish: Calories, Protein, Carbs, Fats, Dietary Fiber, and Sodium with % Daily Values.

- **🗺️ Interactive Campus Map**:
  - Visual campus layout with clickable pins for North Campus, Engineering Quad, Central Plaza, Hostel Block, and South Campus.
  - Quick navigation from map pin directly to today's active menu.

- **🛍️ Student Meal Planner & Tray**:
  - Add items to calculate cumulative meal cost, total calories, total protein, and tray allergen safety.
  - Meal plan swipe eligibility calculator.
  - One-tap order reservation demo with confetti feedback.

- **🎛️ Live Demo Simulator (Outlet Ops)**:
  - Floating simulation bar enabling testers to toggle dish availability (In Stock / Sold Out), cycle rush hour wait times, and open/close outlets in real time.

- **🌓 Dark & Light Mode**:
  - Polished responsive design with smooth transitions and mobile-first navigation.

---

## 🚀 Quick Start

### 1. Install Dependencies
```bash
npm install
```

### 2. Run Local Development Server
```bash
npm run dev
```

### 3. Production Build
```bash
npm run build
```

---

## 🌐 1-Click Deployment Ready

This project is built with **Vite + React + TypeScript + Tailwind CSS** and generates a static single-page application (`dist/`) ready for instant deployment:

### Deploy to Vercel
```bash
npx vercel
```
*Or import the GitHub repository directly into [Vercel](https://vercel.com) — framework preset: **Vite**.*

### Deploy to Netlify
```bash
npx netlify deploy --prod --dir=dist
```
*Or connect your repo to [Netlify](https://netlify.com).*

### Deploy to GitHub Pages
Set `base: './'` in `vite.config.ts` if needed, then run:
```bash
npm run build
```
And deploy the `dist` folder to GitHub Pages.

---

## 🛠️ Tech Stack

- **React 18** + **TypeScript**
- **Vite** (Lightning-fast bundling)
- **Tailwind CSS** (Modern utility styling & dark mode)
- **Lucide React** (Crisp vector iconography)
- **Canvas Confetti** (Interactive micro-celebrations)

