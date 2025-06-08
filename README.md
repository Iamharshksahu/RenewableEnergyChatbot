Renewable Energy Awareness Chatbot
Overview
The Renewable Energy Awareness Chatbot is an AI-powered tool built with Google Dialogflow to educate users about renewable energy sources (solar, wind, hydro, geothermal, biomass) and energy-saving practices. Deployed on Telegram (@RenewableEnergyBot), it handles with ~85% accuracy, answering queries like “India solar?” with reliable facts (e.g., “India’s solar capacity: 92 GW in 2025”). Developed as an internship project, it aims to reduce CO2 emissions by promoting green choices, targeting 10,000 users by July 2025.
Features

Educational Content: Covers solar, wind, hydro, geothermal, biomass, and energy-saving tips (e.g., “LED bulbs save 50–80% energy”).
Interactive: Uses NLP to handle varied inputs and offers follow-up prompts (e.g., “Want to know about solar parks?”) and quizzes (planned).
Reliable Sources: Facts from energy.gov, IRENA, and MNRE (e.g., “20% ethanol blending in 2025”).
Deployment: Live on Telegram, with web integration planned (June 2025).
Scalability: Partnerships with NGOs/schools for educational outreach.

Repository Structure

RenewableEnergyBot.zip/: Dialogflow export folder with ~60 intent JSONs (e.g., ask_india_solar.json, welcome.json) and agent.json.
docs/: Project documentation.
RenewableEnergyBot_AICTE.pptx: AICTE-format presentation.
RenewableEnergyBot_Pitch.docx: Project pitch document.


README.md: This file.

Setup Instructions

Prerequisites:
Google Dialogflow account (free tier).
Telegram account and BotFather for bot creation.
Text editor (e.g., VS Code) for JSON.


Import Dialogflow Agent:
Download RenewableEnergyBot.zip from this repo.
In Dialogflow, go to Settings → Export and Import → Import From Zip → Upload india_intents.zip.


Deploy on Telegram:
Create a bot via @BotFather on Telegram to get a token.
In Dialogflow, go to Integrations → Telegram → Enter token → Enable.
Start bot with /start on Telegram (@RenewableEnergyBot).


Test:
Ask: “India solar?”, “Who are you?”, or “What’s geothermal?”.
Expect ~85% accuracy; report issues in GitHub Issues.



Usage

Try the Bot: Message @GreenEnergy2025Bot on Telegram.
Example Queries:
“India solar?” → “India’s solar capacity: 92 GW in 2025.”
“What can you do?” → “I cover solar, wind, hydro, and more!”


Contribute: Add intents (e.g., ask_quiz) or phrases via pull requests.


Future Work

Add intents: ask_quiz, ask_geothermal, ask_biomass (June 10, 2025).
Deploy web widget (June 12, 2025).
Partner with NGOs/schools to reach 10,000 users (July 2025).
Explore multi-language support (e.g., Hindi).

Contributing

Fork this repo, add intents or docs, and submit pull requests.
Report bugs or suggest features in GitHub Issues.

License
MIT License. See LICENSE file (add manually if needed).
Contact

Harsh Kumar Sahu
Email: harshkumarsahu170405@gmail.com
Telegram: @GreenEnergy2025Bot (try it!)

