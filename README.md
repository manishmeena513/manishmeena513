### Hi there, I'm Manish Meena 👋

I am a software engineer and product designer based in India. I build web software that combines thoughtful product design, practical problem-solving, and client-side systems engineering.

🌐 **Portfolio:** [manishmakes.com](https://manishmakes.com)  
🐙 **GitHub:** [@manishmeena513](https://github.com/manishmeena513)

---

## 📌 About

My engineering work focuses on **local-first, on-device computing**—building web applications where heavy operations (such as document transformation, hardware sensor processing, and complex calculations) occur directly inside the user's browser sandbox without unnecessary cloud exposure.

I care deeply about software that feels like high-calibre physical instrumentation: fast, tactile, accessible, and mathematically sound.

---

## 🚀 Featured Projects

### 1. [FileFixer](https://github.com/manishmeena513/FileFixer) — Flagship Project
> **Universal 100% on-device file studio. Fix your files. Keep them private.**  
> 🔗 **Live Demo:** [filefixer.vercel.app](https://filefixer.vercel.app/)

- **Problem:** Routine file operations—such as compressing images under strict government/visa portal limits, reordering confidential contracts, or scrubbing GPS metadata—traditionally force users to upload personal files to third-party servers.
- **Solution:** A digital workspace containing 20 browser-based file tools with **strictly zero server uploads**. Transformations execute entirely in client memory using Web Workers, HTML5 Canvas, and WebAssembly.
- **Key Technical Details:** Next.js 16 App Router, React 19, Tailwind CSS v4, multi-pass binary search compressor, 4-tier opaque-box test harness (421 automated tests), installable offline-capable PWA.
- **Stack:** TypeScript, Next.js 16, React 19, Tailwind CSS v4, `pdf-lib`, `pdfjs-dist`, `browser-image-compression`, `exifr`, `jszip`, Zustand, IndexedDB (`idb`).

---

### 2. [Mock-Maker](https://github.com/manishmeena513/Mock-Maker) (MockMaster)
> **Competitive exam mock test platform for UPSC CSE, UPPSC & SSC CGL.**  
> 🔗 **Live Demo:** [mockmaster-lyart.vercel.app](https://mockmaster-lyart.vercel.app)

- **Problem:** Many online test series recycle outdated question pools or generate hallucinated AI trivia without syllabus rigor or accurate negative marking.
- **Solution:** A test preparation engine powered by a verified **80% Past Year Questions + 20% AI Model Questions** ratio engine with syllabus-exact marking schemes, isolated mistake retests, and zero gamification distraction.
- **Key Technical Details:** Server-side PostgreSQL with Row Level Security, Google Gemini Flash API with strict JSON schema validation, in-memory streaming ZIP/CSV bulk question ingestion with Zip Slip protection, and a 7-category mistake taxonomy revision workspace.
- **Stack:** TypeScript, Next.js 16, Tailwind CSS v4, Supabase (PostgreSQL), Google Gemini API (`@google/generative-ai`), Zod, JSZip, PapaParse.

---

### 3. [AXIS](https://github.com/manishmeena513/AXIS)
> **Offline-first 3D compass and precision navigation utility.**  
> 🔗 **Live Demo:** [axis-lac-pi.vercel.app](https://axis-lac-pi.vercel.app)

- **Problem:** Navigation apps are frequently bloated, battery-intensive, and fail completely in backcountry areas without cellular service.
- **Solution:** A lightweight, offline-first navigation instrument providing real-time 3D compass orientation, solar/lunar ephemeris (golden hour, blue hour, moon phases), coordinate conversions (DMS, UTM, MGRS), digital spirit levels, and local waypoint marking.
- **Key Technical Details:** Smooth 60fps WebGL 3D compass dial rendered via Three.js, sensor fusion with `DeviceOrientationEvent` and accelerometer APIs, magnetic declination lookup for True vs Magnetic North, and client-side astronomical algorithms.
- **Stack:** TypeScript, Next.js 16, React 19, Three.js (`@react-three/fiber`, `@react-three/drei`), Tailwind CSS v4, Framer Motion, IndexedDB (`idb`), PWA.

---

### 4. [Atmos](https://github.com/manishmeena513/Atmos)
> **Personalizable living weather experience and atmospheric intelligence.**  
> 🔗 **Live Demo:** [atmos-gules-two.vercel.app](https://atmos-gules-two.vercel.app/)

- **Problem:** Weather applications present sterile data grids without explaining how conditions affect daily human routines.
- **Solution:** An ambient weather experience that explains atmospheric trends, detects optimal outdoor activity windows, renders procedural sky particle effects on an HTML5 2D canvas, and features a Glass Studio with 10 custom master presets.
- **Key Technical Details:** High-resolution Open-Meteo atmospheric telemetry models, dynamic CSS variable theme engine with automated WCAG AA luminance contrast guards, Recharts 24-hour telemetry curves, and PWA offline caching.
- **Stack:** JavaScript/React 18, Vite 6, Tailwind CSS, Zustand, Framer Motion, Recharts, HTML5 Canvas.

---

## 🛠️ Tools & Technologies

Supported by real, production-deployed code across my repositories:

- **Languages:** TypeScript, JavaScript (ESNext), HTML5 / Canvas 2D, SQL
- **Frameworks & UI:** Next.js 16 (App Router), React 19 / 18, Vite 6, Tailwind CSS (v4 / v3.4), Radix UI
- **3D & Visuals:** Three.js, `@react-three/fiber`, `@react-three/drei`, Framer Motion, HTML5 2D Canvas
- **On-Device Engines:** `pdf-lib`, `pdfjs-dist`, `browser-image-compression`, `exifr`, `jszip`, Web Workers, DeviceOrientation & Geolocation APIs
- **State & Storage:** Zustand, IndexedDB (`idb`), Supabase (PostgreSQL with RLS), `localStorage`
- **APIs & Data:** Google Gemini API (`@google/generative-ai`), Zod, PapaParse, Recharts, Open-Meteo
- **Testing & Tooling:** Node.js 22 Test Runner (`tsx`), ESLint, Git, Vercel

---

## 🎯 What I Value

1. **Zero-Egress Privacy:** Whenever software can run on the user's hardware, it should. Privacy is not a feature toggle; it is an architectural invariant.
2. **Tactile Instrument UI:** Software should feel like calibrated hardware—responsive controls, physical feedback, minimum $44 \times 44\text{px}$ touch targets, and tabular numbers for numeric alignment.
3. **Rigorous Verification:** Software is defined by its invariants. Automated test harnesses must guard against functional regressions, security leaks, and contrast failures.
4. **No Artificial Bloat:** No dark patterns, no fake countdowns, no gamification streaks, and no unneeded server round-trips.

---

## 📬 Connect

- **Personal Website:** [manishmakes.com](https://manishmakes.com)
- **GitHub:** [@manishmeena513](https://github.com/manishmeena513)
- **Location:** India 🇮🇳
