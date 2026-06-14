# Vamos Ao Museu

Vamos Ao Museu is planned as a web app, later with a mobile version, supported by a Kotlin backend service.

The product goal is to help people find museums near them, discover museum events and offers, and track visits through profile and gamification features.

## Early Scope

- Find museums nearby using a map view.
- Offer a list view with filters such as opening hours, free museums, free entry for Portuguese citizens, and free entry for residents of specific municipalities.
- Find events and offers nearby, such as free-entry days.
- Support museum visit badges and leaderboard-style gamification.
- Provide user profile functionality.

## Repository Layout

```text
apps/
  web/              Web application placeholder.
services/
  backend/          Kotlin backend service placeholder.
docs/
  architecture/     Technical decisions and system design notes.
  product/          Product scope, feature definitions, and discovery notes.
infra/              Infrastructure and deployment configuration placeholder.
design/             Existing design explorations and references.
```

## Open Decisions

- Frontend framework is not chosen yet.
- Kotlin backend framework is not chosen yet.
- Database choice is intentionally undecided. SQL with geospatial support and document-oriented storage should be compared before implementation starts.

## Development Status

This repository has been initialized with a minimal monorepo structure only. Framework scaffolding and database selection are deferred until product and architecture decisions are clearer.
