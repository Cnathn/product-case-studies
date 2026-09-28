[← Portfolio](../README.md)

# Product experiments

### Smaller projects exploring interaction and game design

**Creator:** Taha Can Atahan. All application source remains private. These projects are presented as prototypes or MVPs; no public app-store release is claimed.

## Dishwasher Court

A playful iOS puzzle that turns loading a dishwasher into a sequence of cases and verdicts. The private project is named **Project Meda**; the implemented product is **Dishwasher Court**.

**Stack:** SwiftUI and SpriteKit, with Swift models for dishes, levels, and wash results.

**Implemented scope:** onboarding, interactive placement, dish/rack rules, a set of puzzle cases, scoring, and verdict presentation. SwiftUI hosts the app flow while SpriteKit owns the interactive scene. The level model checks that each case admits a valid physical fit.

**Design challenge:** make constraints understandable through the interaction, then give the result a distinctive comic voice. The separation between level definitions, scene behavior, and verdicts makes those concerns easier to iterate independently.

**Status:** private iOS prototype with public [product](https://cnathn.github.io/dc-court/), [support](https://cnathn.github.io/dc-court/support.html), and [privacy](https://cnathn.github.io/dc-court/privacy.html) pages. Public marketing copy describes the broader concept; this summary reflects the implementation reviewed.

## Main Character Court

A daily social-game MVP where a friend group submits evidence, votes on a charge, and shares a verdict card.

**Stack:** SwiftUI and local application state.

**Implemented scope:** a daily court view, sample evidence feed, voting, an evidence composer, a crew roster, onboarding, an invite/add-friend prototype, and a shareable portrait verdict image.

**Design decision:** explore the social loop with seeded local data before building the multiplayer service. This makes the interaction demonstrable while keeping its current limits explicit.

**Status:** local MVP. Accounts, real invite links, backend storage, real-time voting, remote notifications, and moderation are future work, not delivered capabilities.

## Autopilot Antics

A browser-game prototype built around everyday interactions, including an elevator and a pedestrian crossing.

**Stack:** React, TypeScript, TanStack Start, and CSS animation.

**Implemented scope:** two levels, narration, success/failure feedback, retries, an ending, and locally stored level progress. The game shell coordinates the level components through explicit interaction states.

**Design challenge:** use timing, feedback, and short narrative cues to turn familiar actions into a compact comic game.

**Status:** browser prototype. No public deployment or app-store release was verified.
