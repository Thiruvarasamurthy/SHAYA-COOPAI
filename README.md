# SHAYA COOPAI

Human-first cooperative assistance prototype for an SIH-style civic service concept.

## Prototype flows
- Ask for help: describe a real-life problem without knowing the department.
- Scheme navigator: PM-KISAN, PMFBY and Kisan Credit Card demo routes.
- Cooperative desk: PACS-oriented service navigation.
- Grievance preparation: category, title, description, local save and review. No real complaint is submitted.

## UI direction
The website intentionally avoids the standard AI look: no chat-first layout, no blue-purple neon, no robot imagery, and no dense dashboard aesthetic. It uses warm paper, charcoal, acid-lime, rust and muted cyan; editorial typography; oversized type; asymmetry; tactile surfaces; layered 3D forms; and subtle scroll/reveal motion.

## Technical
Plain HTML/CSS/JavaScript only. No UI framework or external plugin. Drafts use browser localStorage for the prototype.

## Run locally
```bash
python -m http.server 8080 --bind 127.0.0.1
```
Open `http://127.0.0.1:8080`.

## Production
Connect authoritative scheme data, validated multilingual content, authentication, secure documents and approved grievance integrations before production use.