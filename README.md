# SHAYA COOPAI

Human-first cooperative assistance prototype for an SIH-style civic service concept.

## Product idea

SHAYA helps a citizen start from a real-life need instead of forcing them to know a government department or scheme name first. The prototype separates discovery, cooperative services and grievance preparation into clear journeys.

## Technology stack

### Web
- React 18+
- TypeScript
- Vite
- Framer Motion for restrained motion and transitions
- Lucide React for consistent icons
- Custom CSS visual system

### Mobile
- Flutter
- Dart
- Material 3
- Google Fonts

The repository keeps the original static prototype at the root as a lightweight fallback/demo and adds the modern application builds under web/ and mobile/.

## Web prototype

The React version is the primary presentation frontend.

It includes:
- Large editorial hero with layered 3D paper/card composition.
- Four service journeys.
- Scheme navigator with live client-side filtering.
- PM-KISAN, PMFBY and Kisan Credit Card demo routes.
- Help Desk modal with natural-language keyword routing.
- Grievance preparation section.
- Responsive desktop/tablet/mobile layouts.
- Restrained motion rather than flashy AI effects.
- Semantic buttons, links and form controls.

### Run the React app

    cd web
    npm install
    npm run dev

For a production build:

    npm run build
    npm run preview

## Flutter prototype

The Flutter application mirrors the same product language for a future Android/iOS experience.

    cd mobile
    flutter pub get
    flutter run

## Visual direction

The product deliberately avoids the stereotypical AI interface:
- no neon blue/purple AI gradients
- no robot imagery
- no giant chatbot occupying the entire homepage
- no generic admin dashboard
- no excessive glassmorphism
- no fake real-time government integrations

Instead:
- warm paper background
- charcoal information surfaces
- acid-lime interaction accents
- rust and muted-mint supporting surfaces
- editorial typography
- asymmetric composition
- layered physical-card metaphors
- restrained motion
- clear next-step language

## Prototype boundaries

This is a presentation-ready frontend concept, not a production government integration. Scheme content is intentionally small and source-oriented. Grievance interactions are demonstration-only and do not submit a real complaint.

Before production, add:
1. authoritative scheme-data synchronization
2. multilingual content and accessibility testing
3. authentication and consent
4. secure document storage
5. official grievance API integrations
6. audit logging
7. backend validation and rate limiting
8. analytics with appropriate privacy controls

## Legacy static prototype

The root index.html, styles.css and app.js remain available for a zero-build demo:

    python -m http.server 8080 --bind 127.0.0.1

Open http://127.0.0.1:8080.

## Suggested architecture

SHAYA COOPAI
├── web/       React + TypeScript + Vite
│   └── src/   product UI + interaction layer
├── mobile/    Flutter + Dart
│   └── lib/   mobile product UI
└── root       zero-build fallback prototype
