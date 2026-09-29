# Orbit — design brief

## Direction decision
No visual style was selected in the project confirmation, so I considered three distinct directions and chose one to keep implementation decisive:

- **Quiet concierge — 0.07:** An editorial, human-centered organizer with warm paper surfaces, evergreen ink, and restrained citrus accents.
- **Civic control room — 0.04:** A dense, high-contrast command center with cobalt signals, compact data grids, and terminal-like operational clarity.
- **Pocket greenhouse — 0.06:** An expressive consumer ritual tracker with soft lilac, botanical shapes, playful motion, and collectible progress.

**Committed direction: Quiet concierge.** Orbit should feel like a thoughtful chief of staff, not another alarm-heavy project manager. Use decisive information hierarchy and confident urgency while making the experience feel calm.

## Design movement
Contemporary editorial productivity: the clarity of a well-designed financial journal with the approachable warmth of a personal concierge.

## Core principles
- Prioritize the next meaningful action over total task volume.
- Make recommendation rationale visible (due date, cost exposure, past pattern, user preference).
- Keep money and completion actions explicit; never imply a live payment or account connection in the demo.
- Treat attention as scarce: show fewer, more useful alerts.
- Preserve control: a suggested action is never a transaction authorization.

## Color philosophy
Warm oat/ivory canvas (#F5F3ED), paper cards (#FFFEFB), deep evergreen ink (#18362F), muted forest accent (#4F7964), and a restrained tangerine signal (#E69B55). Use gold/amber only for meaningful urgency and dusty red for imminent risk. Maintain clear contrast and do not colorize every component.

## Layout paradigm
Desktop app shell with a quiet evergreen navigation rail and a broad editorial content canvas; responsive bottom navigation / slide-in navigation on narrow screens. Pair a large focus card with a compact obligation queue, then insight and workflow modules. Prioritize scan-friendly cards and pill labels over dense tables.

## Signature elements
- The “Today, taken care of” hero with a clear focus recommendation.
- Thin orbit/route motif in the Orbit emblem.
- A transparent “why this?” rationale chip on every smart recommendation.
- Calm progress ring for monthly life-admin load and small channel/source tokens.

## Interaction philosophy
Immediate, reversible feedback for local changes. Use modal sheets for create/edit/review flows, with clear primary and secondary actions, a visible close path, and a concise next step. Confirmation must clearly identify simulated actions. Use undo-capable toasts where appropriate. Avoid blocking wizards.

## Animation
Subtle 160–220 ms easing for menus, modals, and state transitions; low-motion by default, with `prefers-reduced-motion` respected. No looping decorative movement, confetti, or urgent pulsing.

## Typography system
A system sans-serif for interface text and a compact editorial display face using the local system serif stack for prominent headlines. Use clear size/weight contrast, comfortable line lengths, tabular numerals for money and dates, and never depend on a remote font service.

## Brand essence
Orbit gives busy people more headspace by noticing what is coming and organizing the next small step.

## Brand voice
Warm, specific, composed, and action-oriented. Prefer “You could save $18 by renewing early” over “URGENT ALERT.” Make prototype versus connected-service boundaries plain and matter-of-fact.

## Wordmark / logo
Use the lowercase wordmark **orbit** in a crisp, friendly sans-serif paired with a geometric orbit/check symbol: one open evergreen ring, a clear check path, and a small amber node. The symbol must remain legible as a favicon. Use the same mark in the navigation rail and app metadata.

## Signature brand color
Deep evergreen **#18362F**.
