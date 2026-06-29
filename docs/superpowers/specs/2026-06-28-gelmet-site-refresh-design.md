# Gelmet Site Refresh Design

## Goal

Tighten the Gelmet website so it feels like a distinct creative technology studio with real product energy, clearer brand voice, stronger app storytelling, and a repo structure that stays easy to maintain.

## Scope

This pass focuses on three things:

1. Strengthen the homepage so it feels more like a real studio front door and less like a generic placeholder.
2. Expand the apps page so Spot Projector and SpotMover read like real products with use cases, status, and direction.
3. Add lightweight maintenance structure in the repo so future site edits stay easy for Codex and easy to publish.

## Design Direction

The site should stay restrained, dark, glossy, and technical, but the copy should feel more lived-in and specific. Gelmet is not just “a company that makes apps.” It is a studio identity that happens to include apps, consulting, and AI work. The homepage should reflect that hierarchy.

The home page should answer:

- what Gelmet is
- what kinds of work it does
- why its work feels different
- which apps are currently the clearest proof of the studio

The apps page should answer:

- what each app is for
- who it helps
- what stage it is in
- why it exists in the first place

## Content Model

### Homepage

The homepage should lead with studio identity, then move quickly into capabilities and featured work. It should feel like a compact but intentional studio overview.

Recommended sections:

1. Hero with stronger studio framing
2. Studio capability grid
3. Featured apps with richer detail
4. Studio approach / working philosophy
5. Clear CTA into apps and contact

### Apps Page

The apps page should become more product-focused. Each featured app should have a richer card or section with:

- product name
- stage
- platform
- core problem it solves
- target audience
- what makes it different

It should also include a small forward-looking section for future tools without pretending they are finished.

## Visual Direction

The existing visual system is a good base. Keep:

- dark glassy panels
- the Gelmet mark
- rounded forms
- strong spacing

Add:

- larger product sections
- more visual hierarchy between “studio” and “app” content
- lightweight product metadata rows
- stronger CTA grouping

## Maintenance Structure

The repo should include one lightweight document that explains:

- where the main pages live
- which files to edit for homepage, apps, and styling
- how publishing works

This is not a CMS. The goal is clarity, not overengineering.

## Success Criteria

The refresh is successful if:

1. The homepage feels more distinct and brand-specific.
2. The apps page feels like a real product overview, not a placeholder list.
3. The repo remains simple enough that future edits are just HTML/CSS changes plus a push to `main`.
