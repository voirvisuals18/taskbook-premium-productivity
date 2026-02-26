# TASKBOOK - THE PREMIUM MINIMALIST PRODUCTIVITY SUITE

Taskbook is a modern, high-performance productivity application developed with Flutter. It provides a unified interface for managing tasks, notes, and calendar events with a focus on speed, privacy, and refined aesthetics.

## CORE FEATURES

### . Unified Interface
- Tasks: Priority-based management with integrated category filtering.
- Notes: Versatile note-taking with both grid and list view support.
- Calendar: Comprehensive event tracking with global search and recurring event logic.

### . Intelligence & Search
- Relevance Engine: Search results are automatically prioritized using a weighted system (Exact Match > Starts With > Partial Match).
- Real-time Counters: Dynamic headers that display the total number of items found during an active search.

### . Premium Design System
- VIP Aesthetics: Implementation of soft shadows, depth-based layouts, and smooth micro-animations.
- Adaptive Theming: Full support for both Light and Dark modes with customizable accent colors.
- Fluid Transitions: Navigation via a standard Material 3 system for a stable and premium user experience.

### . Interactive Personalization
- Hold-to-Select Header: A unique interaction allowing users to customize the header icon by holding it for 800ms.
- Visual Progress: An integrated circular progress stroke and scale-down animation provide tactical feedback during interaction.
- Custom Input: Support for manual entry of any single symbol to be used as a persistent header identity.

### . Privacy & Reliability
- Offline Architecture: All user data is stored locally using the Isar Database.
- Zero Tracking: No external cloud dependencies or telemetry.
- Data Portability: Robust backup system allowing full export and import of tasks, notes, events, and settings via JSON.

---

## TECHNICAL SPECIFICATIONS

### . Framework & Logic
- SDK: Flutter (Material 3)
- State Management: Riverpod
- Database: Isar (High-performance NoSQL)
- Local Storage: Shared Preferences (Metadata & UI Settings)

### . Project Structure
- lib/data: Schemas, models, and Isar database services.
- lib/providers: Business logic and reactive state management.
- lib/screens: Context-specific UI views for each module.
- lib/widgets: Highly reusable architectural components.

---


## ARCHITECTURAL GOALS

The primary goal of Taskbook is to provide an elite user experience while maintaining absolute data sovereignty. It is designed for users who require a fast, clean, and private alternative to cloud-based productivity suites.

---

v2.16.0

