# Cut Protocol

## Brand Foundation

**Tagline:** Results On A Deadline  
**Positioning:** Deadline-driven body transformation for people who need results, not motivation speeches.  
**Core promise:** Know where you stand. Get a plan. Execute.

### Tone
- Direct
- Tactical
- Clean
- Disciplined
- Confident
- Not reckless or cheesy

## Brand Kit

### Visual identity
Performance, precision, urgency, control.

### Colors
- Charcoal black: `#111315`
- Deep slate: `#1A1F24`
- Signal red: `#D83A34`
- Steel gray: `#707A84`
- Off white: `#F3F5F7`
- Success green: `#2E9B62`
- Warning amber: `#E4A72D`

### Typography
Use **Inter**.

### Logo / icon direction
- CP monogram with subtle measurement motif
- Matte dark background + bold red or white CP mark
- No overly detailed or novelty fitness iconography

## Product Scope

### Primary audiences
- Military members preparing for standards
- People cutting weight for a deadline
- Athletes making a weight class

### Secondary audiences
- Civilians leaning out for events
- Users who want structure over generic advice

### App flow (v1)
1. Onboarding (welcome, goal, audience, baseline, assessment)
2. Home dashboard (status, countdown, today’s actions)
3. Assessment/calculator modules
4. Protocol engine
5. Daily logging and trend tracking
6. Protocol library
7. Education section
8. Subscription/paywall

### Main navigation
- Home
- Plan
- Log
- Progress
- Library

## Core Logic (Backend)

### Data model
- **User:** profile, baseline metrics, target date, goal type, subscription
- **DailyLog:** weight, waist, calories, protein, water, movement, sleep, notes
- **Protocol:** duration, intensity, rules, day-by-day instructions, safety notes
- **Assessment:** status, gap, projection, recommendation

### Engines
1. Baseline status engine
2. Deadline urgency score (`0–30` on track, `31–60` caution, `61–100` aggressive required)
3. Projection engine
4. Adherence score (weighted daily score out of 100)
5. Rule-based protocol recommendation engine

## Protocol Catalog

- 24 Hour Tighten Up
- 48 Hour Emergency Cut
- 72 Hour Cut Protocol
- 7 Day Aggressive Cut
- 14 Day Controlled Cut
- Maintenance / Reverse Out

Each protocol includes hydration, nutrition, sodium/carb guidance, movement, recovery, and risk labels.

## Safety Requirements

Hard stops/flags for:
- Extreme target loss rate
- Dizziness, dehydration, fainting reports
- Very low body weight/BMI
- Large reduction goals with short deadlines
- Repeated excessive rapid drops

Safety response:
- Prompt to slow down
- Restrict to controlled protocol where needed
- Hydration/recovery reminders
- Medical-clearance guidance when appropriate

## MVP Requirements

Build first:
- Onboarding
- Assessment/calculator
- Dashboard
- 3 protocols: 48h, 72h, 7-day
- Daily logging
- Simple progress charts
- Subscription setup

Do not build yet:
- Barcode scanner
- Smartwatch integrations
- Social feed
- AI chatbot
- Coach marketplace
- Community challenges

## Recommended Stack

- Frontend: FlutterFlow or React Native
- Backend: Firebase
- Database: Firestore
- Auth: Firebase Auth
- Payments: Stripe (web), RevenueCat (mobile)

## App Store Identity

- **Title:** Cut Protocol
- **Subtitle:** Results On A Deadline
- **Short description:** Assess status, track key metrics, and execute structured weight-cut plans around real deadlines.

## Execution Priorities

1. Lock brand (name + tagline)
2. Build clickable mockup
3. Draft first 3 protocols
4. Implement calculator logic
5. Launch landing page + waitlist
