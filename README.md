# AETHER — AI / ML Team Website

Internal branding portal for the applied AI / ML team. Showcases projects, hosts demo videos and tutorials, and connects to Jira / Confluence.

> `AETHER` is a working placeholder name — to be replaced with the real team name.

## Status

Design / prototype phase. The visual design has been locked via an interactive mockup.

- **[`aether-preview.html`](aether-preview.html)** — full single-scroll homepage mockup (open in a real browser; uses canvas animation).
- **[`logo-concepts.html`](logo-concepts.html)** — logo direction explorations (Concept B, neural network, selected).

## Design system

- **Look & feel:** high-end, futuristic; 2-tone (dark hero → light content → dark footer).
- **Hero:** dark navy with a 3D *growing* glassmorphic neural network (nodes as glass orbs, signal pulses, mouse-steered rotation).
- **Cards:** frosted glassmorphic panels on dark glowing "stages", with 3D tilt-on-scroll.
- **Palette:**  — deep navy `#00263A`, bright cyan `#00AEEF`, deeper blue `#0a6ed1`, on white/light.
- **Logo:** neural-network mark (input → hidden → output layers).

## Intended build (Phase 1)

- **Stack:** Next.js (App Router) + TypeScript + Tailwind + react-three-fiber + Framer Motion.
- **Auth:** Microsoft Entra / Azure AD SSO, gated by AD group membership.
- **CMS/DB:** Postgres + Prisma.
- **Scope:** foundation + branding + project showcase + login + CMS/DB foundation.

### Roadmap

- **Phase 1** — foundation, branding, project showcase, login, CMS/DB.
- **Phase 2** — media: self-hosted demo videos + tutorials.
- **Phase 3** — live Jira / Confluence read-only integration.
