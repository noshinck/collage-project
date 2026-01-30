Presidency Campus Navigator 🎓

A professional, interactive campus navigation web application designed for Presidency University. This single-page application (SPA) allows students to visualize building layouts, track real-time security guard locations, and earn points through community contributions.

🌟 Key Features

🗺️ Interactive Mapping

Campus Overview: A stylized grid layout representing 8 major campus buildings around a central animated plaza.

Detailed Floor Plans: Click on any building to zoom into detailed views with architectural schematics.

Visual Feedback: Pulse animations indicate live activity or security presence.

🛡️ Real-Time Intelligence

Guard Tracking: Students can drop "Guard" pins to alert others of security personnel locations.

Community Reports: Report crowded canteens, empty library spots, or charging station availability.

Live Feed: A scrolling 3D-tilted feed showing recent campus activity.

🏆 Gamification

Points System: Earn points for contributing accurate map data.

Leaderboard: Weekly rankings tracking top student contributors.

Ranks: Progress from "Newbie" to "Campus Legend" based on participation.

🎨 Modern UI/UX

Professional Aesthetic: Built with a "Stripe-like" design language using glassmorphism, mesh gradients, and clean typography (Plus Jakarta Sans).

Smooth Animations: Powered by GSAP for premium entrance effects, scroll triggers, and micro-interactions.

Responsive: Fully optimized for mobile devices and desktop screens.

🛠️ Tech Stack

This project uses a lightweight, serverless architecture ideal for rapid deployment and high performance.

Core: HTML5, Vanilla JavaScript (ES6+)

Styling: Tailwind CSS (via CDN)

Animations: GSAP (GreenSock) + ScrollTrigger

Icons: Lucide Icons

Data Persistence: Browser localStorage (No backend required)

🚀 Getting Started

Since this is a client-side application with no build step required, running it is instant.

Prerequisites

A modern web browser (Chrome, Edge, Safari, or Firefox).

An active internet connection (to load CDNs for Tailwind, GSAP, and Fonts).

Installation

Download the index.html file.

Open the file directly in your browser.

# Or using a simple local server (optional)
npx serve .


📖 Usage Guide

Login: Enter any Student ID (e.g., "Student123") on the landing page to create a session.

Explore: Click "Explore Map" to see the campus grid.

Drop a Pin:

Select a Building (e.g., "Main Block").

Click anywhere on the map layout.

Choose a category (Guard, Info, Food, etc.) to report.

Check Ranks: Visit the Leaderboard tab to compare your points with others.

📂 Project Structure

The entire application logic is contained within a single file for portability:

index.html: Contains structure, styles, and logic.

<head>: CDN imports and Tailwind config.

<body>: View containers (Splash, Auth, Dashboard).

<script>:

State Management (state object).

Rendering Logic (renderMap, renderBuildingDetail).

Animation Logic (GSAP Timelines).

🔮 Future Enhancements

[ ] Pathfinding algorithm for turn-by-turn navigation.

[ ] Backend integration (Firebase/Supabase) for global real-time data.

[ ] 3D Building models using Three.js.

[ ] Class schedule integration.

Presidency Campus Navigator - Navigate Smarter.
