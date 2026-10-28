# Pavan Kumar Chowdary Kothapalli — AI Systems Portfolio

A high-performance, responsive portfolio website showcasing AI engineering, Large Language Models (LLMs), autonomous multi-agent systems, and scalable backend infrastructure.

## Stack & Architecture

- **Markup & Content:** Semantic HTML5 (`index.html`)
- **Styling & Animations:** Pure CSS3 (`style.css`) with custom design tokens, keyframes, and micro-interactions
- **Interactions:** Lightweight vanilla JavaScript for IntersectionObserver scroll reveal, scroll spy navigation, dynamic copyright, and clipboard copy

## Key Features

- **Resume-Accurate Information:** Updated to reflect role at Tata Consultancy Services (TCS), Brainovision experience, full skill stack (LangGraph, FastAPI, MCP, Azure, AWS IAM/STS, Redis), education, and certifications.
- **Featured Projects:**
  - AI-Driven Incident Triage & Auto-Remediation Agent (Dynatrace, GitHub PR automation, HITL governance, Jira API)
  - Enterprise Cloud Operations AI Agent (Model Context Protocol / MCP, LangGraph, AWS IAM SSO & STS AssumeRole)
  - Waywork — Real-Time Commute & Carpooling App (MapLibre, OpenStreetMap, PostgreSQL row-locking, WebSockets)
  - Big Data Engineering Project With Azure (Azure Data Factory, Databricks, Synapse Analytics, MongoDB)
- **Transitions & Animations:**
  - **Hero Entrance:** Fluid staggered fade-in-up animations on load.
  - **Live Indicator:** Real-time pulsing glow badge for current TCS AI Engineer status.
  - **Scroll Reveal:** Smooth viewport-triggered reveals using `IntersectionObserver`.
  - **Card Hover Effects:** Subtle lift, border illumination, and soft ambient drop shadows.
  - **Animated Architecture Diagram:** Dynamic SVG flow with animated dash patterns representing live MCP queries and IAM tool routing.
  - **Interactive Navbar & Scroll Spy:** Active section highlighting and blurred glassmorphism on scroll.
  - **Interactive Copy Email:** One-click copy with floating toast confirmation.
  - **Accessibility:** Full `prefers-reduced-motion` compliance.

## Preview Locally

Simply open `index.html` in any modern web browser or serve it with Python/Node:

```bash
# Python
python -m http.server 8000

# or Node / npx
npx serve
```

## Deployment

The site is purely static and zero-dependency, deployable instantly to:
- **GitHub Pages:** Push to `pavanchowdary-2612.github.io`
- **Vercel / Netlify:** Drag-and-drop or run `vercel --prod`
- **AWS S3 + CloudFront:** Sync static assets to an S3 bucket configured with CloudFront OAC.
