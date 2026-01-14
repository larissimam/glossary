An interactive, multilingual reference tool built for Localisation Efficiency. This application provides instant access to standardized terminology and marketing definitions for NVIDIA’s latest hardware and software ecosystems, including the GeForce RTX 50 Series and Blackwell Architecture.

🚀 Overview
The GeForce Glossary is designed for localization teams (NALA), partners and marketing professionals who need consistent technical terminology across multiple languages. It serves as a single source of truth for product definitions, supporting English (EN), Portuguese (PT), Spanish (ES), and French (CA).

✨ Key Features
Multilingual Search: Search for terms in any of the four supported languages in real-time.

Dual Definition Modes: Access full technical definitions for desktop/web and concise "mobile-optimized" versions for smaller UI footprints.

Split-View Interface: A modern interactive UI that allows browsing the list while viewing detailed "Lexicon Mapping" and "Regional Context" side-by-side.

One-Click Copy: Integrated clipboard functionality for rapid asset localized string retrieval.

Category Filtering: Filter terms by Hardware, Software, Thermal Design, Architecture, and more.

Secure Access: Protected by a SHA-256 hashed password entry screen for internal use.

🛠️ Technical Stack
Frontend: HTML5, Tailwind CSS (Utility-first styling).

Icons: Lucide-Icons for a modern, crisp UI.

Data Structure: data.json serves as a lightweight, portable NoSQL database.

Security: Web Crypto API for SHA-256 password verification.

Typography: Google Fonts (Inter).

📂 Project Structure
Plaintext

├── index.html    # Main application logic and UI
├── data.json     # Multilingual database of terms and definitions
└── README.md     # Documentation
