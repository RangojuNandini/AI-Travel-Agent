## 🌍 AI Travel Agent  ##

An automated AI-powered travel planner built using **n8n**, **Google Gemini**, and **Email automation**.

___🚀 Overview___

AI Travel Agent is an intelligent workflow that automatically creates customized travel plans for users.
It collects destination details through a form, processes the data using an LLM (Google Gemini), and sends a structured travel itinerary to the user’s email in seconds.


__This project demonstrates:__

-AI integration

-Workflow automation

-Real-world form handling

-Email delivery

-Low-code/no-code engineering using n8n



🧩 __Workflow Architecture__

**Form Submission** ➜ **Code Node** ➜ **Gemini LLM** ➜ **Email Sender**



__1. Form Trigger__

Collects:

-Destination

-Number of people

-Budget (₹ / $)

-Number of days

__2. Code Node__

Formats the user input into a clean LLM prompt.

__3. Gemini LLM__

Generates:

-Transport options

-Hotel suggestions

-Day-wise itinerary

-Local experiences

-Safety tips

__4. Email Node__

Sends the AI-generated travel plan to the user’s email.


___✨ Features___

✔ Collects user travel inputs.
✔ Builds complete AI-based travel plans.
✔ Uses Google Gemini for reasoning.
✔ Sends results automatically via email.
✔ Fully no-code (except one JS node).
✔ Easy to import and run in any n8n instance.


___🛠 Tech Stack___
-Component	Technology
-Workflow Automation	n8n
-AI Model	Google Gemini
-Email Service	SMTP / Gmail
-Custom Logic	JavaScript
-Input Handling	n8n Form Trigger

__📸 Demo__

[▶️ Click here to watch the demo]  -> https://drive.google.com/file/d/1UZgfiHzQZq6oM7rkwCJA4bogAq8SmXpU/view?usp=sharing








