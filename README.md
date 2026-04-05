README
Transport Shuttle OS
Digital Transformation Prototype — Mirembe Muse

What This Is
Transport Shuttle OS is an interactive proposal prototype built by Mirembe Muse to present a full 12-month digital transformation engagement to a transport business client in the Eastern Cape, South Africa.
The prototype replaces a static PDF proposal with a fully navigable, clickable interface that demonstrates the system's capabilities — including a live admin dashboard preview, an interactive WhatsApp booking flow demo, feature deep-dives, and a complete pricing and ROI breakdown.
This repository contains two deliverables:

transport-shuttle-os.html — The interactive proposal prototype
case-study.md — The written case study documenting the engagement


The Engagement
Client type: Owner-operated transport business, Eastern Cape, South Africa
Services: Scholar transport, corporate events, airport transfers
Fleet: 2 × 14-seat passenger vehicles
Engagement: Tier 3 Vision System — 12-month digital transformation partnership
Total standard value: R197,500+
Founding client investment: R106,000 (R40,000 + R5,500/month × 12)
Client saving: R91,500+ (46% below market rate)

Prototype Features
The HTML prototype is fully self-contained — no dependencies, no server required. Open in any modern browser.
Navigation
Fixed top navigation bar with smooth scroll to five sections: Overview, Phases, Dashboard, Pricing, and ROI. Active section is highlighted automatically on scroll.
Feature Roadmap
Three collapsible phase cards covering all 16 system features. Each feature tile opens a modal with a full description and feature checklist. A Tier 2 / Tier 3 toggle is available at the top of the section.
Admin Dashboard Preview
A simulated admin dashboard with six switchable panels: Overview (KPIs + charts), Bookings, Revenue (route profitability), Customers (lifetime value rankings), Routes, and Reviews (reputation dashboard with AI-drafted responses). All panels are interactive.
WhatsApp Automation Demo
A live chat simulation demonstrating the automated WhatsApp booking flow. The user can click through a full multi-step booking conversation for scholar transport, corporate events, or airport transfers — including button-driven flows, instant confirmations, and booking reference generation.
Pricing Section
Side-by-side Tier 2 and Tier 3 pricing cards with full feature lists, payment structure details, and a visual four-step payment milestone timeline.
ROI Breakdown
Three-tab section covering Tier 2 component breakdown, Tier 3 component breakdown, and retainer service details — each with a savings banner showing the discount against standard market rates.
Feature Modals
Every feature tile in the roadmap section opens a detailed modal with a description, tier label, and a full checklist of what is included. Modals are dismissible by clicking the close button or clicking outside.

File Structure
transport-shuttle-os/
├── transport-shuttle-os.html   # Interactive prototype (self-contained)
├── case-study.md               # Written case study
└── README.md                   # This file
No build step. No package manager. No external dependencies beyond Google Fonts (loaded via CDN). The prototype works offline if fonts have been cached, or with a minor visual degradation if they have not.

Technology
The prototype is built with vanilla HTML, CSS, and JavaScript — no frameworks.
LayerApproachLayoutCSS Grid + FlexboxTypographySyne (display), DM Mono (body), Instrument Serif (accent) via Google FontsColour systemCSS custom properties (design tokens)AnimationsCSS transitions + keyframes; IntersectionObserver for scroll revealsInteractivityVanilla JS — no jQuery, no frameworksDataAll content hardcoded inline; no API callsCompatibilityModern browsers (Chrome, Firefox, Safari, Edge)
The prototype is intentionally dependency-free so it can be sent as a single file attachment, opened from a desktop, shared via link, or embedded in a client portal without any setup.

Design System
The visual language uses a dark futuristic aesthetic built around the following tokens:
--bg:       #03050a   Background (near-black)
--bg2:      #080c14   Card background
--bg3:      #0d1220   Elevated surface
--cyan:     #00e5ff   Primary accent (Tier 2, headings, links)
--teal:     #00c4a7   Secondary accent (positive states, growth)
--purple:   #8b5cf6   Tier 3 accent (premium, vision)
--gold:     #f59e0b   Warning, highlights, optional features
--red:      #ff4d6a   Negative states, alerts
--text:     #e8edf5   Primary text
--muted:    #5a6a88   Secondary text, labels
--border:   rgba(0,229,255,0.1)   Subtle borders
Typography scale uses Syne 800 for display headings, DM Mono 400 for body and UI, and Instrument Serif italic for accent phrases.

The Two Tiers
Tier 2 — Growth System
Investment: R25,000 (standard value: R61,500)
Timeline: 5–6 weeks
Focus: Foundation and automation
Covers everything needed to go from invisible to operational: professional website, Notion business hub, Supabase booking system with API integration, 24/7 rule-based chatbot, 60-post automated social media package, and Google Business optimisation. Optional monthly retainer at R3,500/month.
Tier 3 — Vision System
Investment: R40,000 + R5,500/month × 12 months
Timeline: 12-month phased rollout
Focus: Intelligence, loyalty, and strategic partnership
Everything in Tier 2, plus: WhatsApp Business API with official verification, GPT-powered multilingual AI chatbot, predictive analytics dashboard, automated reputation management, dynamic pricing engine, customer loyalty programme (Bronze–Platinum), driver mobile app (optional), and a full strategic partnership with referral commissions, co-marketing, and QR code vehicle branding.

Payment Structure (Tier 3)
MilestoneAmountTimingDepositR12,000 (30%)Project startPhase 1 completeR12,000 (30%)Week 6Phase 2 milestonesR8,000 (20%)Months 3–6Phase 3 completeR8,000 (20%)Month 12Monthly retainerR5,500/monthMonth 1–12

About Mirembe Muse
Mirembe Muse is a digital transformation studio based in East London, South Africa. The practice builds integrated digital operating systems for owner-operated and small-to-medium businesses — combining web development, automation, AI integration, content strategy, and ongoing strategic partnership into single coherent engagements.
Transport Shuttle OS is one vertical expression of that model, built specifically for the operational and commercial realities of the Eastern Cape transport sector.
Contact
hello@mirembemuse.co.za
084 291 6742
East London, South Africa

Transport Shuttle OS prototype and case study produced by Mirembe Muse. Client identity anonymised.
