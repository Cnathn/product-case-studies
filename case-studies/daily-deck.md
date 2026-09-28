[← Portfolio](../README.md)

# Daily Deck

### Vocabulary practice built around a small daily habit

**Creator:** Taha Can Atahan<br>
**Platform:** Web interface with an iOS Capacitor project<br>
**Status:** Implemented product with release preparation; App Store availability not verified<br>
**Source:** Private

[Support](https://cnathn.github.io/app-support/daily-deck/support.html) · [Privacy](https://cnathn.github.io/app-support/daily-deck/privacy.html)

## Product and ownership

Daily Deck turns vocabulary practice into short, swipeable sessions with completion history, streaks, and reminders. My work covers the daily learning loop, multilingual content presentation, progress tracking, the mobile interface, and iOS integration and release preparation.

## Implementation

The app uses **React, TypeScript, TanStack, Tailwind CSS, and Capacitor**. Its vocabulary model supports English, Czech, German, French, Spanish, Italian, and Turkish. Bundled vocabulary and local progress support an offline learning flow; advertising features have separate connectivity requirements.

The current implementation builds five-word daily decks and a separate optional bonus deck. Progress is stored by target language, so switching languages does not mix completion histories. The data layer includes migration from the earlier single progress record.

## Decisions and challenges

- **Stable daily content:** deterministic deck ordering gives the user a repeatable daily session instead of reshuffling the experience on every visit.
- **Language-specific progress:** separate learning histories preserve meaning when a user studies more than one language.
- **Local persistence:** a storage abstraction handles progress and settings without making account creation a prerequisite for the learning loop.
- **Mobile packaging:** a static Capacitor entry supports the iOS bundle alongside the web application structure. Safe-area spacing, dynamic viewport sizing, touch gestures, and theme changes require mobile-specific handling.
- **Reminders and optional rewards:** local notifications support the habit loop; rewarded-ad completion governs optional bonus access.
- **Content provenance:** the private project records vocabulary data sources and attribution. This portfolio does not redistribute that dataset.

## Release context

The project includes an iOS target, native integration modules, and an App Store readiness checklist. Some checklist entries describe earlier stages of the project, so they are not treated as proof of current submission status.

Public support and privacy pages are available. A matching App Store listing was not verified, and no download link or published-release claim is included here.

**What this project demonstrates:** designing a small learning loop, managing multilingual state, and carrying a web experience into an iOS delivery workflow.
