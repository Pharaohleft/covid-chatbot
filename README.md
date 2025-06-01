# covid-chatbot
 Project Title:
COVID-19 Auto Chat — also referred to as the COVID Chat-Bot.

🟢 What It Is:
A chatbot system designed to provide reliable COVID-19 information using IBM Cloud’s AI services. It can answer FAQs about COVID-19, get live data (like case numbers), and even pull in trusted news articles — automating answers and reducing the load on human support lines.

🟢 The Problem It Solves:
During COVID, many people needed info quickly (symptoms, testing sites, resources, etc.).

Human systems were overwhelmed — so the chatbot uses AI to instantly provide answers, letting human teams focus on complex cases.

🟢 Key Technologies & How It Works:
✅ IBM Watson Assistant: The core AI that understands questions and provides answers.
✅ IBM Watson Discovery: Searches live news articles for relevant updates.
✅ IBM Cloud Functions (OpenWhisk): Connects to APIs and performs logic (like getting COVID stats).
✅ IBM Speech to Text & Text to Speech (in voice-enabled version): For spoken interaction.
✅ Node.js web server: Hosts the chatbot interface for websites.
✅ Slack Integration: Lets users chat directly from Slack.
✅ Node-RED: Visual flow tool that manages data between services and supports voice-based interactions.

🟢 Three Deployment Modes:
1️⃣ Website: Chatbot embedded in a site.
2️⃣ Slack: Direct messages in Slack.
3️⃣ Voice-Enabled (Node-RED): Voice interface for websites.

🟢 How It Works (Example for Website):
User types a question on the website.

Node.js server sends the question to Watson Assistant.

Assistant uses NLU (natural language understanding) to figure out what they’re asking.

If needed, it calls APIs (like CDC’s or Johns Hopkins) for data updates.

Watson Discovery fetches the latest news on COVID-19.

The final answer is shown on the website.

🟢 Your Project Tasks & Learning Outcomes:
Setup: Registered for IBM Cloud, created a Watson Assistant instance.

Integration: Connected the Assistant to real-time data via webhooks.

Testing: Deployed and tested the chatbot to answer questions like “What are the symptoms of COVID-19?”

Project Title: COVID-19 Auto Chat / COVID Chat-Bot
Institution: Don Bosco Institute of Technology, Mumbai
Course: Final Year Computer Engineering, Cloud Computing Lab
Timeframe: 2021-2022

🌟 Purpose of the Project
To ease the load on overwhelmed communication systems during COVID-19 by providing quick, reliable information via a chatbot.

Provide trusted, real-time data on COVID-19 (symptoms, testing sites, news) to the public.

Help people avoid misinformation and keep them updated.

🔧 Main Technologies & Services
✅ IBM Watson Assistant: Core chatbot engine; understands questions and responds.
✅ IBM Watson Discovery: Scans live news sources for COVID updates.
✅ IBM Cloud Functions (OpenWhisk): Executes actions, like fetching data or calling APIs.
✅ IBM Speech to Text & Text to Speech: For voice-based interaction (like asking verbally on a site).
✅ Node.js: Runs the web server for chatbot interactions.
✅ Slack: Chatbot integrated with Slack for workplace communications.
✅ Node-RED: Visual programming tool to enable voice conversations (microphone input/output).

🌍 Deployment Modes
1️⃣ Website Chatbot
2️⃣ Slack Integration
3️⃣ Voice-enabled Node-RED interface

This flexibility broadens access — helping both consumers and teams.

🧩 How it Works (End-to-End)
1️⃣ User asks a question (like “Where can I get tested?”).
2️⃣ IBM Watson Assistant parses the question’s meaning.
3️⃣ If live data is needed, IBM Cloud Functions fetch COVID stats from trusted APIs (e.g., Johns Hopkins).
4️⃣ IBM Watson Discovery scans reputable news sites for relevant COVID articles.
5️⃣ Watson Assistant crafts a clear response.
6️⃣ Web page or Slack shows the chatbot’s answer instantly.
7️⃣ In the voice version, Speech to Text turns user’s voice into text; Text to Speech speaks the chatbot’s answer back.

🖥️ Implementation
IBM Cloud setup: Registered for IBM Cloud, provisioned Watson services.

Webhook configuration: Connected chatbot to external data APIs.

Skill-building in Watson: Created “COVID Crisis Communication” dialog skill.

Testing & verification: Deployed live previews and tested across channels.

Voice interaction: Used Node-RED to turn audio into chatbot queries.

📊 Your Learning Outcomes
Mastered chatbot building using Watson Assistant.

Understood API integrations for dynamic data retrieval.

Learned to combine text-based and voice-based interactions.

Experienced with cloud services orchestration — linking multiple IBM Cloud tools.

Gained exposure to real-world public health use cases of AI.

Mastered IBM Watson Assistant for real-world NLP.

Learned to integrate APIs and external data.

Understood how to handle dynamic, real-time data in crisis communication
