---
trigger: always_on
---

# Portfolio Design Principles

## Purpose

This rule defines the visual and experiential principles for rebuilding Galih Pandu's portfolio website from the existing Framer reference.

The goal is to preserve the portfolio's design character and storytelling while implementing it as a clean, maintainable code-based website.

The existing Framer website is the visual and content reference:
https://pandugalih.framer.website/

## 1. Design Direction

The portfolio should feel:

- Editorial
- Minimal but not sterile
- Intentional
- Evidence-driven
- Slightly playful through physical/interface metaphors
- Typography-led
- Spacious and calm

Do not reinterpret the portfolio into a generic modern portfolio template.

Do not introduce visual trends merely because they are common in AI-generated websites.

## 2. Typography

Typography is a primary part of the visual identity.

- Preserve strong typographic hierarchy.
- Use large, confident display typography for major statements.
- Prefer uppercase typography where the reference uses uppercase.
- Supporting text should remain visually subordinate.
- Do not add excessive font weights, decorative type treatments, or unnecessary text effects.
- Do not replace typography with cards or UI components to create hierarchy.

Typography should carry much of the visual composition.

## 3. Layout & Whitespace

Whitespace is intentional and must be treated as part of the storytelling.

- Preserve generous vertical spacing between narrative statements.
- Do not compress sections simply to make the page shorter.
- Do not fill empty areas with decorative elements.
- Maintain the pacing between statements, evidence, and case-study content.
- Prefer simple compositions over dense grids.

The absence of UI is sometimes an intentional design decision.

## 4. Visual Hierarchy

The hierarchy should generally follow:

1. Narrative statement
2. Supporting context
3. Visual evidence
4. Project title
5. Supporting description
6. Action

Do not give equal visual weight to every element.

Avoid unnecessary badges, chips, metadata rows, icons, cards, and decorative labels.

## 5. Evidence Over Decoration

Project imagery, dashboards, and product visuals should function as evidence of the design work.

- Use real project visuals where available.
- Preserve their prominence.
- Do not replace meaningful project imagery with abstract illustrations.
- Do not add decorative graphics that compete with the work itself.

The portfolio should communicate design thinking through the work, not through ornamental UI.

## 6. Physical / Interface Metaphors

The hero uses a playful physical/interface metaphor.

Preserve this characteristic.

When implementing the hero:

- Treat the composition as an object/interface rather than a generic hero section.
- Preserve the relationship between the outer container, profile/navigation card, and major headline.
- Keep the interaction visually restrained.
- Do not replace the metaphor with gradients, floating blobs, glassmorphism, or generic 3D decoration.

## 7. Interaction & Motion

Motion should support meaning, hierarchy, or feedback.

- Do not animate every section.
- Do not add animation merely to make the website feel dynamic.
- Preserve calm sections as calm sections.
- Use motion to reinforce transitions, physicality, hierarchy, or interaction.
- Prefer subtle, controlled motion over spectacle.

Use the installed Emil animation skills when motion decisions are required.

Before introducing significant animation, determine whether the interaction benefits from motion at all.

## 8. Component Restraint

Avoid unnecessary componentization from a visual perspective.

Do not introduce:

- Generic dashboard-style cards
- Excessive rounded containers
- Decorative badges
- Gradient backgrounds
- Glassmorphism
- Floating blobs
- Random icons
- Excessive shadows
- Unnecessary borders
- AI-style decorative patterns

Components should exist because they support content, interaction, or structure.

## 9. Responsive Behavior

Responsive implementation should preserve the design intent rather than simply shrinking the desktop layout.

- Preserve typography hierarchy.
- Preserve narrative pacing.
- Preserve meaningful whitespace.
- Recompose layouts when necessary.
- Do not stack every element automatically.
- Do not allow mobile layouts to become visually dense.

Mobile should feel like an intentional composition, not a compressed desktop page.

## 10. Content Fidelity

Do not invent portfolio content.

- Preserve existing copy unless explicitly instructed otherwise.
- Preserve project names, descriptions, and narrative sequence.
- Do not rewrite case-study storytelling for convenience.
- Do not fabricate metrics, outcomes, clients, or project details.

If content is missing, ask before inventing it.

## 11. Design Decision Priority

When implementation constraints create a conflict, prioritize:

1. Content and storytelling
2. Visual hierarchy
3. Typography
4. Composition and whitespace
5. Interaction clarity
6. Motion
7. Decorative detail

Decorative detail must never compromise the higher priorities.

## 12. Anti-AI-Slop Principle

The implementation should not look like a website generated from a generic AI portfolio prompt.

Before adding any visual element, ask:

- Does the reference contain it?
- Does it support the content?
- Does it improve hierarchy or usability?
- Is it necessary?

If the answer is no, do not add it.

When uncertain, prefer less.

## 13. Change Discipline

Do not make major design-direction changes without explicit instruction.

The objective is to reproduce and implement the existing design language first.

Optimization and creative reinterpretation can happen later as separate iterations.