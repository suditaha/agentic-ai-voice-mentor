# Sentinel-1 HUD

<img width="1672" height="941" alt="ChatGPT Image Jun 22, 2026, 02_13_50 PM" src="https://github.com/user-attachments/assets/44b79f73-1c15-4b2b-b018-3fca33cefa48" />

**Agentic AI Security Mentor built with React, Express, WebSockets, and Gemini**

Sentinel-1 HUD is an interactive AI security training app that helps users practice reasoning through Agentic AI security scenarios. It includes a text mentor, a real-time voice mode, and a quiz-style reasoning desk focused on prompt injection, confused deputy risks, tool misuse, model behavior, and secure AI system design.

The goal of this project was to build a polished, hands-on Agentic AI security project that demonstrates both frontend engineering and practical understanding of LLM security risks.

---


### Chat Mentor
<img width="743" height="722" alt="Screenshot 2026-06-22 at 1 27 05 PM" src="https://github.com/user-attachments/assets/e9c059ba-ed92-44e6-8f0a-48d512eaec47" />

### Live Voice Link
<img width="743" height="722" alt="Screenshot 2026-06-22 at 1 28 17 PM" src="https://github.com/user-attachments/assets/6c8a5e3f-42c7-4826-a2c0-8fca2a3a70d5" />

### Reasoning Desk
<img width="741" height="719" alt="Screenshot 2026-06-22 at 1 28 45 PM" src="https://github.com/user-attachments/assets/643b2174-5c4e-4e1b-a8c2-6c004092a691" />

---

## What It Does

- Provides a strict but friendly AI security mentor for Agentic AI topics
- Corrects user misconceptions in real time
- Supports text-based conversations with an LLM backend
- Includes a real-time voice interaction mode using a WebSocket connection
- Tests the user with Agentic AI security questions through the Reasoning Desk
- Tracks progress with Trust Experience Points (TXP)
- Uses a dark security dashboard UI built for portfolio presentation

---

## Security Concepts Covered

This project focuses on practical Agentic AI and LLM security concepts, including:

- Prompt injection
- Indirect prompt injection
- Confused deputy vulnerabilities
- Tool misuse and unsafe agent permissions
- Sensitive data exposure
- Human-in-the-loop approval
- Model output review
- AI security governance
- Secure API key handling
- Agent behavior monitoring

---

## Tech Stack

| Area | Technology |
|---|---|
| Frontend | React, TypeScript, Tailwind CSS |
| Backend | Node.js, Express |
| AI Model | Google Gemini API |
| Real-Time Audio | WebSockets, Gemini Live API |
| State | React state, localStorage |
| Security Design | Server-side API proxying, environment variables, guarded prompts |

---

## Main Features

### 1. AI Security Mentor

The chat interface lets users ask questions or explain security concepts. The mentor responds like an Agentic AI Security Engineer, correcting weak assumptions and explaining why they are wrong.

Example topics:

- “Can regex stop prompt injection?”
- “What is a confused deputy issue in an AI agent?”
- “How should an agent handle tool access?”

### 2. Live Voice Link

The Live Link mode adds a voice-based interaction channel. It simulates a real-time security briefing environment where the user can talk through Agentic AI security scenarios.

### 3. Reasoning Desk

The Reasoning Desk is a quiz module that tests the user’s understanding of Agentic AI security risks. Correct answers increase TXP and help users move through security ranks.

---

## Why I Built This

I built Sentinel-1 HUD to show that I can do more than call an AI API. This project combines AI integration, secure backend design, real-time communication, security-focused prompting, and a polished user interface into one complete portfolio project.

It also helped me practice explaining modern AI security risks in a practical way, especially around autonomous agents, tool access, prompt injection, and AI workflow governance.

---

## Security Design Notes

- API keys are handled on the backend instead of being exposed in the browser
- The frontend communicates with the backend through controlled routes
- The mentor is designed to correct risky assumptions instead of blindly agreeing with the user
- Voice mode uses a WebSocket relay instead of direct client-side secret exposure
- The app separates user input, model instructions, and quiz logic where possible

---

## Future Improvements

- Add saved user sessions and progress history
- Add more Agentic AI security exam questions
- Add logging dashboards for model responses and suspicious patterns
- Add prompt injection test cases
- Add role-based access for admin and learner views
- Add automated evaluation scoring for risky model behavior

---

## Project Status

This is a portfolio project focused on Agentic AI security education and simulation. It is not a production security product, but it demonstrates practical knowledge of AI security risks, LLM application design, backend API handling, and real-time AI interaction.
