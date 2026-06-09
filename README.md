📌 About MotoTrack
MotoTrack is a smart, pure client-side web application (Single Page Application) meticulously engineered to track your motorcycle's spare part lifespans and service intervals in real-time.

Built with a strict 100% Privacy-Focused & Offline-First philosophy, MotoTrack handles all your maintenance schedules, odometer logs, and financial records directly inside your browser's localStorage. No sign-ups required, no cloud backends, and absolutely zero personal data tracking. Your data never leaves your device.

🚀 Key Features
Central Odometer Synchronization: Simply update your motorcycle's current global mileage, and the app instantly re-evaluates the remaining precise lifetime for every configured component.

Dynamic Early Warning System (EWS): Visualizes your components' health using clear, modern color-coded alerts:

🔴 Critical: Component lifetime has expired or exceeded safe thresholds.

🟡 Warning: Component is approaching its replacement limit (customizable global/individual thresholds).

🟢 Good: Component is well within its optimal operating condition.

Adaptive Tracking Intervals (Fast & Slow Moving): * Fast Moving: Dual-tracking metric combination based on both mileage (KM) and duration (Months)—ideal for Engine Oil, Gear Oil, or Brake Fluid.

Slow Moving: Single-metric tracking based strictly on mileage intervals—perfect for V-Belts, Spark Plugs, or Clutch Plates.

Detailed Maintenance Ledger: Maintain an organized logbook of part replacements featuring exact dates, odometer values during service, workshop locations, itemized pricing, and custom mechanic notes.

Data Sovereignty (JSON Export/Import): Since there is no server-side database, you own your data completely. Backup or migrate your data across devices (e.g., from your phone to a laptop) seamlessly via a single, lightweight .json file export.

Modern & Responsive UI: Experience a sleek cyber-industrial Dark Mode or a clean Light Mode. Built to be fully responsive for seamless mobile navigation and desktop layout ergonomics.

Native Bi-Lingual Support: Dynamic multi-language localized toggles (Indonesian & English) without page refreshes.

💻 Tech Stack
HTML5 & CSS3 (Custom Utility Variables)

Tailwind CSS v3 (Rapid UI layout framework)

Vanilla JavaScript (ES6+) (Zero-dependency modern state architecture)

LocalStorage API (Persistent browser storage sandbox)

⚙️ How to Run Locally
Since MotoTrack runs completely on the client-side, you do not need to install complex runtimes like Node.js, configure Docker, or spin up backend database services.

Clone or download this repository:

Bash
git clone [https://github.com/username/mototrack.git](https://github.com/username/mototrack.git)
Navigate into the project folder and launch the web interface:

Simply double-click the moto-track.html file to open it instantly inside any modern browser (Chrome, Edge, Firefox, Brave, or Safari).

Alternatively, use the Live Server extension in VS Code for an optimized local development experience.
