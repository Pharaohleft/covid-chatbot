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

Learning Outcome:

Mastered IBM Watson Assistant for real-world NLP.

Learned to integrate APIs and external data.

Understood how to handle dynamic, real-time data in crisis communication
