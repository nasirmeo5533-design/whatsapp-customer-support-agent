# Abeer Nasir — Personal AI Agent

An AI chatbot that knows everything about **Abeer Nasir** — his experience, skills, agency (Open Agent), services, pricing, case studies, testimonials, and goals. Built with pure HTML, CSS, and JavaScript — zero APIs, zero backend, zero database.

[![Built with OpenCode](https://img.shields.io/badge/Built%20with-OpenCode-BE185D?style=flat-square)](https://opencode.ai)

## Overview

This AI agent is trained exclusively on Abeer Nasir's personal and professional data. It can answer questions about:

- **Personal background** — Bio, story, location, contact
- **Open Agent** — His agency, process, mission
- **8 Services** — Meta Ads, Shopify, AI Automation, AI Agents, AI Content, Web Dev, Paid Ads, Social Media
- **Pricing** — Starter (PKR 30K), Premium (PKR 50K), Pro (PKR 80K)
- **Experience** — Generative AI Specialist, Digital Marketing Specialist, Author
- **Skills** — 4 categories across AI, Marketing, E-Commerce, Content
- **Case Studies** — 4 documented results with real numbers
- **Testimonials** — Client feedback
- **FAQ** — 14 commonly asked questions

## File Structure

```
/
├── index.html              Chatbot UI (HTML + CSS + JS)
├── data/
│   └── personal-data.json  All personal and business data
└── README.md               This file
```

## How to Customize

Edit `data/personal-data.json` to update any information:

- `person` — Name, title, bio, contact, social links
- `agency` — Company name, description, pricing, process
- `services` — List of services with descriptions
- `skills` — Skill categories and items
- `experience` — Work history timeline
- `caseStudies` — Results and achievements
- `testimonials` — Client quotes
- `faq` — Questions and answers
- `suggestions` — Suggested questions for the UI

## UI Features

- Google-style suggestion chips (clickable)
- Clean, minimal white interface
- Typing indicator
- Smooth animations
- Context-aware follow-up suggestions
- Responsive (mobile + desktop)

## Deployment

Deploy as a static site on Vercel or GitHub Pages.
