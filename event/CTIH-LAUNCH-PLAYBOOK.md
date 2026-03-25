# Coastal Talent and Innovation Hack-A-Thon (CTIH) — Launch Playbook

## Overview
The CTIH Hack-A-Thon is a hybrid (in-person + virtual) event bringing together developers, creators, entrepreneurs, and AI innovators.

## System Architecture

### Event Website (foai.cloud/event/)
- **Landing Page**: Event info, schedule, tracks, prizes, sponsor preview
- **Registration**: Attendee sign-up with Stripe checkout (In-Person $149 / Virtual $49)
- **Sponsor Page**: Platinum/Gold/Silver tiers with inquiry form
- **Success Page**: Post-payment confirmation with next steps

### Backend (AIMS Event API)
- Registration & lead capture → Firestore
- Stripe Checkout session creation
- Stripe webhook → payment confirmation → access token generation
- Sponsor inquiry capture & onboarding flow
- Access token verification for event day

### Marketing Automation (Chicken Hawk)
- Lead nurture email sequences (attendee + sponsor + virtual)
- Social media campaign scheduling
- Notification dispatch (email, SMS, push)
- Analytics & KPI tracking

### AI Concierge (Agent ACHEEVY-009)
- Event FAQ handling
- Registration guidance
- Sponsor tier explanation
- Event day support

### Supporting Services
- **Destinations AI**: Travel & accommodation for in-person attendees
- **GRAMMAR**: Content style consistency across all communications
- **Per|Form**: Team performance tracking & judging system
- **LUC**: Budget tracking for event operations
- **Locale by ACHIEVEMOR**: Multi-currency sponsor payment support

## URLs for AI SEO
| URL | Purpose |
|-----|--------|
| https://foai.cloud/event/ | Main landing page |
| https://foai.cloud/event/register.html | Registration & tickets |
| https://foai.cloud/event/sponsors.html | Sponsor information |
| https://foai.cloud/event/success.html | Post-payment confirmation |
| https://foai.cloud/event/sitemap.xml | SEO sitemap |

## Sponsor Tiers
| Tier | Price | VIP Passes | Key Benefits |
|------|-------|------------|-------------|
| Platinum | $10,000 | 10 | Main stage branding, keynote slot, premium booth |
| Gold | $5,000 | 5 | Stage branding, workshop slot, standard booth |
| Silver | $2,500 | 2 | Logo placement, table at networking area |

## KPI Targets
- 500+ attendees
- $50,000 revenue target
- 10+ sponsors
- 70% satisfaction rate

## Launch Checklist
- [ ] Event website live at foai.cloud/event/
- [ ] Stripe checkout tested (test mode)
- [ ] Email sequences configured in n8n
- [ ] ACHEEVY event concierge trained
- [ ] Social media campaigns scheduled
- [ ] Sponsor outreach begun
- [ ] SEO sitemap submitted to search engines
- [ ] Analytics tracking verified
