# houseofgyi-tracker
House of Gyi CENTCOM

OSINT Tracker for Chameleon Carrier Transparency


🕊️ To Aimee and Lucas Cardoso,
At exactly 10:45 in the morning on August 26, 2023, your bestie, Erika, received a call from Shasta delivering the most difficult news any human being should ever have to hear: “Aimee and Lucas are no longer with us.”

I was standing on the opposite side of the kitchen island. My sister completely lost it.

Just a few weeks before, I had been slowly recouping from the unnecessary emotional trauma, distress, and familial distrust that my parents and sister had caused. They had mistakenly perceived my new girlfriend of seven months, Maw Gyi, as an overseas romance scammer stealing hearts and money. I felt emotionally betrayed and extremely hurt by this misconceived notion. The strain was so heavy that Maw Gyi and I seriously contemplated walking away from each other's lives and breaking up for good.

Thankfully, a few weeks later, my parents and my sister emotionally reconciled with me and Maw Gyi, profoundly apologizing for the misunderstandings and the pain they had caused.

Then, August 26, 2023, arrived. In an instant, the renewed peace and mutual understanding our family had just found was completely shattered.

Now, I am channeling that grief into action. Building this OSINT tracker and writing this code is my form of closure and emotional resolution. By exposing the "Chameleon Carriers" that try to hide their dangerous histories, I am building a mechanism for accountability. This project is my way of ensuring the shadows of the logistics industry are illuminated, so no other family has to stand in their kitchen and hear that kind of news.




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
