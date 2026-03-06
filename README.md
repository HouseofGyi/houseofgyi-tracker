# houseofgyi-tracker

House of Gyi CENTCOM

House of Gyi CENTCOM

OSINT Tracker for Chameleon Carrier Transparency

🕊️ In Memory of Aimee & Lucas Cardoso
This project is dedicated to the memory of Aimee and Lucas. Our goal is to ensure that no trucking company can hide a history of negligence behind a new name or DOT number. Through data and transparency, we seek to protect families and hold high-risk operators accountable.

🛡️ Project Overview
House of Gyi is an Open Source Intelligence (OSINT) platform designed to identify "Chameleon Carriers"—transportation entities that frequently reincarnate to evade safety violations, inspections, and legal liabilities.

By centralizing federal safety data, corporate filings, and archived digital footprints, we create a "One Roof" view of a carrier's true ancestry.

🛠️ The Technical Stack
Infrastructure: Cloudflare Zero Trust with secure origin cloaking via Cloudflare Tunnels.

Backend: Serverless logic using Cloudflare Workers (JavaScript).

Integrations: * FMCSA QCMobile API: Real-time federal safety and registration data.

OpenCorporates API: Mapping shared officers and addresses across TX/OK.

Wayback Machine API: Recovering deleted digital history of defunct entities.

🚦 Development Roadmap
[x] Phase 1: Infrastructure & Secure Tunneling.

[x] Phase 1.5: GitHub Repository & CI/CD Deployment.

[ ] Phase 2: Live FMCSA API Integration (WebKey Authentication).

[ ] Phase 3: Cross-Reference Logic for "Chameleon" Detection.

⚖️ Licensing
Software: All code in this repository is licensed under the GNU GPLv3.

Content: All investigative reports, mission documentation, and media are licensed under CC BY-SA 4.0.

📋 Setup & Contribution
Since this is a secure OSINT tool, certain environment variables (like the FMCSA_WEBKEY) are stored as encrypted Cloudflare Secrets and are not public.

"Information is the first step toward accountability."
