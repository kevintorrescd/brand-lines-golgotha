---
name: presentation-pptx
description: Create or adapt PPTX/PowerPoint educational presentations using the user's established visual brand. Use when the user asks for slide decks, PowerPoint templates, PPTX generation, presentation visual guidelines, educational modules, simulacros, reading-analysis decks, or any presentation that should follow the existing style: #f8fafc backgrounds, black titles, #4b5563 body text, #059669 green accents, white cards, #e5e7eb borders, and #ff4444 error states.
---

# Presentation PPTX

## Purpose

Use this skill to create, revise, or evaluate PPTX/PowerPoint presentations so they match the user's educational visual system. The style is clean, academic, modern, structured, and highly legible.

For detailed rules, read `references/visual-guidelines.md` when creating a full deck, auditing visual consistency, or making design decisions beyond a single slide.

## Hard Color Rules

Use only this core palette unless the user explicitly overrides it:

- Slide background: `#f8fafc`
- Main title: `#000000`
- Titles: `#111111`
- Body / text boxes: `#4b5563`
- Primary green: `#059669`
- Soft green / subtitle backgrounds: use `rgba(5, 150, 105, 0.47)` or visual equivalent `#CFF8E2`
- Positive block background: `#ecfdf5`
- Card border: `#e5e7eb`
- Card background: `#ffffff`
- Error / negation: `#ff4444`
- Error background: `#fef2f2`
- Neutral reading/table block: `#f3f4f6`

Do not introduce marfil, beige, dorado, blue, teal, purple, or decorative gradients.

## Typography

Prefer:

- Titles: Montserrat ExtraBold, Inter ExtraBold, Aptos Display Bold, or Arial Black.
- Body: Inter, Aptos, Segoe UI, or Arial.

Use heavy black titles, lighter secondary text, and generous line height. Do not justify paragraphs.

## Core Layout Patterns

Use these patterns as the default deck vocabulary:

- Strong cover: `#f8fafc` background, huge black left-aligned title, subtitle in `#4b5563`, no cards.
- Cover with lateral image: left column with pill, title, subtitle; right side large real educational photo.
- 2x2 concept grid: white cards with `#e5e7eb` borders; optional green-soft positive card and red-soft error card.
- Simulacro question: long soft-green pill, bold question, divider, answer options as white bordered cards, letter chips in `#f3f4f6`.
- Feedback slide: long soft-green pill, correct answer block in `#ecfdf5` with left `#059669` border, then two explanatory columns.
- Reading/case slide: pill, large black title, wide neutral reading block with left green border.
- Comparative table: large title with short green line, clean wide table, header on light background, green line under header, neutral alternating cells.

## Component Rules

Cards:

- Use `#ffffff` background, `#e5e7eb` border, 8-12 px radius.
- Use `#ecfdf5` only for positive/active cards.
- Use `#fef2f2` only for error, negation, or key warning cards.
- Keep card text short; use bold only for keywords.

Pills:

- Use soft green fill and `#059669` text.
- Use uppercase labels: `ITEM 1`, `CASO 3`, `AREA 1`, `RETROALIMENTACION ITEM 3`.
- Make them slim, rounded, and often full-width on question/feedback slides.

Accent lines:

- Use `#059669`.
- Use short lines beside titles or as a left border for reading/feedback blocks.
- Do not overuse as decoration.

## Assets

Available assets:

- `assets/presentation-template.pptx`: PowerPoint template deck demonstrating the approved layouts.
- `assets/paleta-guia-visual.png`: official palette preview.

When creating a new PPTX and the user wants this style, start from `assets/presentation-template.pptx` when practical, or recreate its rules directly.

## Workflow

1. Identify the slide type: cover, concept grid, question, feedback, reading/case, table, or image cover.
2. Apply the hard color rules first.
3. Use the closest core layout pattern.
4. Keep one dominant idea per slide.
5. Verify no forbidden colors or gradients were introduced.
6. For complete decks, read `references/visual-guidelines.md` and use the template PPTX as a visual reference.

## Quick Visual Checklist

- Background is `#f8fafc` or white.
- Titles are black and strong.
- Body text is `#4b5563`.
- Cards are white with `#e5e7eb` borders.
- Green is used for structure, correct answers, pills, and active states.
- Red is used only for error, negation, or distractors.
- No marfil, dorado, blue, teal, or decorative gradient appears.
