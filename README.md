# CloudLove 💕

## Project Overview

**CloudLove** is an interactive, cyberpunk-themed romantic declaration web application. It's a creative love confession presented as a futuristic "AI compatibility analysis system."

### What It Does

The project takes users through a multi-screen interactive experience designed to:

1. **Collect Personal Insights** — Users input their current thoughts/feelings and answer detailed questions about:
   - Trauma patterns and emotional triggers
   - Preferred forms of affection and love languages
   - Ideal date configurations
   - Core relationship values and trust pillars
   - Hidden personality preferences (with playful Easter eggs)

2. **Simulate AI Analysis** — The application "decrypts" user responses using Google Gemini API to generate a personalized behavioral profile and compatibility assessment.

3. **Reveal the Match** — After passing verification screens, the app reveals the predetermined "compatible candidate" — Ricardo (the developer/creator).

4. **Deliver the Message** — The full experience culminates in a heartfelt romantic message formatted as an elegant handwritten letter.

---

## Technical Features

- **Cyberpunk/Hacker Aesthetic** — Dark theme with neon red (#e63946) accents, monospace typography, terminal-style elements, and CRT screen effects (scanlines + grain animation)
- **Multi-Screen Navigation** — Seven interconnected screens with smooth transitions and progress indicators
- **Interactive Forms** — Trauma scales (0-5), affection preferences (multiple choice), 0-10 rating system, and car selection with images
- **API Integration** — Google Gemini 3.5 Flash for dynamic AI-generated compatibility analysis
- **Responsive Design** — Adapts gracefully to mobile devices
- **ASCII Art & Theming** — Terminal-style UI with blinking cursors, live "hacker logs," and password prompts

---

## Project Structure
  CloudLove/ 
  ├── index.html # Single-page application with all screens + styling
  ├── coracao.png # Heart icon (favicon) 
  ├── IMG_*.webp # Candidate profile photo (Ricardo) 
  └── README.md # This file

  
---

## Screen Flow

| Screen | Title | Purpose |
|--------|-------|---------|
| **01** | INPUT INICIAL | Capture initial thoughts/feelings |
| **02** | MAPEAMENTO PSI | Quiz: trauma inventory + affection preferences |
| **03** | PROTOCOLO DE DESCRIPTOGRAFIA | Personality verification questions |
| **04** | LOGIN RESTRITO | Token validation (password prompt) |
| **05** | TERMINAL GEMINI | Live AI analysis processing |
| **06** | ANÁLISE FORMAL | Gemini-generated compatibility report |
| **07** | CARD CANDIDATO | Ricardo's profile reveal + final message |

---

## Technologies Used

- **HTML5** — Semantic markup
- **CSS3** — Advanced styling (CSS Grid, Flexbox, animations, gradients, pseudo-elements)
- **Vanilla JavaScript** — Form handling, screen navigation, state management
- **Google Gemini API** — Dynamic personality analysis
- **Responsive Design** — Mobile-first approach with media queries

---

## How It Works

### User Journey
1. User enters a thought/feeling (max 120 chars)
2. Answers ~15 multi-part questions about emotional patterns and preferences
3. Completes personality verification challenges
4. Enters a decryption token to "unlock" the analysis
5. Watches live terminal logs as Gemini processes their data
6. Receives AI-generated compatibility analysis (99.8% match — predetermined)
7. Views Ricardo's candidate profile with relationship stats
8. Reads the romantic declaration

### Key Easter Eggs & Details
- **Q16 & Q17** contain subtle personality clues (drummer weakness, IT nerd attraction)
- **Q18** features car options with actual images — selecting "BYD Seal" has special handling
- **Gemini Integration** generates unique analysis based on user inputs while maintaining the predetermined outcome
- **Terminal effects** simulate real-time hacking/decryption with animated logs

---

## Deployment

Host `index.html` on any static hosting service:
- GitHub Pages
- Vercel
- Netlify
- AWS S3 + CloudFront

No backend server required (Gemini calls are made client-side with API key).

---

## License

Personal project. Created with love as a romantic gesture. 💕

---

## Author's Note

This is a creative, tech-forward love confession that combines:
- **Technical skill** in web development
- **Cyberpunk aesthetics** for a futuristic vibe
- **Personal touches** (questions tailored to inside knowledge)
- **Surprise reveal** (the compatibility "system" is actually just leading to you)

If you're receiving this, it means someone put genuine effort into making their feelings known in the most geeky, creative way possible. 🚀❤️

