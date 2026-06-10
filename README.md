#  Nayra AI

<div align="center">

### Built on Sarvam AI to Explore Sovereign Voice Infrastructure for India

A production-ready Text-to-Speech application powered by Sarvam's Bulbul v3 voice model.

</div>

---

## Why I Built This

While building AI products for Indian users, I repeatedly encountered the same problem:

Most global voice models treat Indian languages as secondary experiences.

Pronunciation quality, code-switching, regional language support, and natural conversational flow often break down when serving Indian audiences.

Nayra AI was built as an exploration of how sovereign AI infrastructure can deliver significantly better experiences for Indian users.

Instead of relying on generic global voice APIs, this project integrates Sarvam AI's Bulbul v3 model to provide speech generation optimized for Indian languages and accents.

---

## What This Project Demonstrates

### Sarvam AI Integration

- Direct integration with Sarvam Text-to-Speech APIs
- Bulbul v3 voice synthesis
- Dynamic voice profile selection
- Secure API key handling
- Real-time audio generation
- Downloadable speech output

### Product Engineering

- End-to-end API integration
- Error handling and validation
- Client-side state management
- Responsive UI architecture
- Browser storage management
- Real-time playback controls

### India-First AI Experience

- Hindi support
- English (India) support
- Bengali
- Tamil
- Telugu
- Marathi
- Gujarati
- Kannada
- Malayalam
- Punjabi

---

## Technical Stack

| Layer | Technology |
|---------|------------|
| Frontend | HTML5 |
| Styling | Tailwind CSS |
| Application Logic | JavaScript |
| Voice Generation | Sarvam Bulbul v3 |
| Icons | Font Awesome |
| Deployment | GitHub Pages |

---

## Architecture

text User Input     ↓ Language Selection     ↓ Voice Profile Selection     ↓ Sarvam AI API     ↓ Bulbul v3 Inference     ↓ Audio Generation     ↓ Playback & Download 

---

## Key Engineering Decisions

### Dual Engine Design

The application supports:

1. Sarvam AI for production-quality speech synthesis
2. Native browser voices as a fallback layer

This approach ensures graceful degradation when API access is unavailable.

### Local API Key Storage

API credentials are stored locally in the browser rather than being proxied through a backend service, keeping deployment simple while allowing users to experiment directly with Sarvam APIs.

### Lightweight Deployment

The entire application runs as a static frontend deployment, making it easy to host and scale while demonstrating direct integration with Sarvam's infrastructure.

---

## What I Learned

Building Nayra AI reinforced a belief I already had while working on AI products for Indian users:

Infrastructure matters.

The quality difference between models optimized for Indian languages and generic global alternatives becomes obvious once real users begin interacting with the system.

Projects like Sarvam are important because they are building foundational AI infrastructure designed specifically for India's linguistic diversity rather than treating it as an afterthought.

---

## Developer

### Saurav Thakur

Full Stack Developer • AI Engineer

GitHub: https://github.com/sauravthakurq

LinkedIn: https://linkedin.com/in/sauravthakurq

Email: sauravthakur6310@gmail.com

Portfolio: https://sauravthakurx.vercel.app

---

 
---

Built with Sarvam AI and a strong belief that India needs world-class sovereign AI infrastructure.
