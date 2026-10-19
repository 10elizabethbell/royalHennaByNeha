---
name: Royal Henna by Neha
description: A henna artist's page you can put henna on. Warm skin ground, wine and rani bands, a cone that pipes real paste.
colors:
  skin: "#d6a476"
  skin-lit: "#dfb085"
  ink: "#3a0d27"
  ink-soft: "#5e2443"
  wine: "#4a1131"
  rani: "#a3205a"
  cream: "#fbefe6"
  cream-soft: "#f3d6df"
  marigold: "#f4a53a"
  stain: "#7a2410"
  stain-fresh: "#e9913f"
  stain-mid: "#b8461a"
  paste: "#2b1b0e"
  error: "#6e0820"
typography:
  display:
    fontFamily: "Iowan Old Style, Palatino Linotype, Palatino, Book Antiqua, Georgia, serif"
    fontSize: "clamp(2.45rem, 11.2vw, 5.4rem)"
    fontWeight: 700
    lineHeight: 0.96
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Iowan Old Style, Palatino Linotype, Palatino, Book Antiqua, Georgia, serif"
    fontSize: "clamp(2rem, 8.6vw, 3.6rem)"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.01em"
  title:
    fontFamily: "Iowan Old Style, Palatino Linotype, Palatino, Book Antiqua, Georgia, serif"
    fontSize: "1.375rem"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.02em"
  list-title:
    fontFamily: "Iowan Old Style, Palatino Linotype, Palatino, Book Antiqua, Georgia, serif"
    fontSize: "1.25rem"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "0.01em"
  wordmark:
    fontFamily: "Iowan Old Style, Palatino Linotype, Palatino, Book Antiqua, Georgia, serif"
    fontSize: "1.125rem"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.14em"
  aside:
    fontFamily: "Iowan Old Style, Palatino Linotype, Palatino, Book Antiqua, Georgia, serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: "0.02em"
  body:
    fontFamily: "system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 700
    lineHeight: 1
  small:
    fontFamily: "system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.55
rounded:
  focus: "6px"
  field: "12px"
  card: "14px"
  pill: "999px"
spacing:
  gut-phone: "16px"
  gut-desk: "32px"
  stack-xs: "10px"
  stack-sm: "12px"
  stack-md: "20px"
  stack-lg: "26px"
  band-phone: "52px 0 60px"
  band-desk: "72px 0 84px"
components:
  button-fill:
    backgroundColor: "{colors.wine}"
    textColor: "{colors.cream}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-fill-hover:
    backgroundColor: "{colors.rani}"
    textColor: "{colors.cream}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.wine}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-line-hover:
    textColor: "{colors.rani}"
  button-marigold:
    backgroundColor: "{colors.marigold}"
    textColor: "{colors.wine}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-marigold-hover:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.wine}"
  service-row:
    textColor: "{colors.cream}"
    typography: "{typography.list-title}"
    padding: "8px 0"
    height: "64px"
  service-row-arrow-hover:
    backgroundColor: "{colors.marigold}"
    textColor: "{colors.wine}"
    size: "44px"
  chip:
    backgroundColor: "rgba(251,239,230,.55)"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "44px"
  chip-selected:
    backgroundColor: "{colors.wine}"
    textColor: "{colors.cream}"
  input:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "12px 14px"
    height: "52px"
  link-card:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.wine}"
    rounded: "{rounded.card}"
    padding: "14px 20px"
    height: "84px"
---

# Design System: Royal Henna by Neha

## Overview

**Creative North Star: "Henna on Skin"**

The page is skin, and the ink on it is henna. The ground everywhere outside the bands is warm skin (`skin`); every decorative mark is drawn live by a canvas henna cone in wet brown-black paste that dries, crumbles off, and leaves a stain that deepens from fresh orange to maroon. Nothing ornamental is a static image: the hero mandala and every lace edge between sections are piped by the same engine from one mark grammar of line, petal, dot and scallop. Visitors can pipe their own paste with a finger or mouse, and it stains the same way.

Color commits by whole band, not by accent. Sections are either bare skin, fully drenched wine (`wine`), or fully drenched rani pink (`rani`), taken from Neha's flyer; each band boundary is a scalloped skin cuff carrying a henna lace border. Marigold (`marigold`) is the one hover and celebration accent. Type is the owner's house rule: system fonts only, with the system serif (Iowan Old Style, Palatino, Georgia) setting every heading in bold uppercase to echo the "ROYAL" serif on her flyer, and the system sans for everything you read or tap.

Density is phone-first and generous: one column, 16px gutters, 44px minimum touch targets, big pill buttons. The page refuses the category default of a photo-grid salon page with a pink script logo.

**Key Characteristics:**
- Warm skin ground; wine and rani bands drenched edge to edge
- Every ornament is live-piped henna that dries and stains (paste, stain-fresh, stain-mid, stain)
- One mark grammar: line, petal, dot, scallop, reused in every lace edge and mandala
- System serif headings, bold and uppercase; system sans body (house rule)
- Pills for actions, 12-14px soft corners for fields and cards, scallops at section seams
- Marigold signals hover on dark bands; rani outlines signal hover/focus on form controls

## Colors

A warm henna palette: skin ground, two drenched flyer colors for bands, one marigold accent, and a four-step paste-to-stain ramp that only the henna engine uses.

### Primary
- **Wine Band** (`wine`): the dominant brand color. Fills whole bands (occasions, close, footer), the primary filled button, the Instagram card's arrow disc and the selected chip. Behind each wine band the lace edge's skin cuff sits on wine.
- **Rani Pink** (`rani`): the flyer pink. Fills the "See my work" band edge to edge with white text; it is also the hover state of filled and outlined buttons on skin, the focus-ring color on skin, the selection highlight, the scrollbar thumb, the caret, and the hover/focus outline of every form control. The cone's band is painted rani.

### Secondary
- **Marigold** (`marigold`): the celebration and hover accent. The service-row arrow fills marigold on hover/focus; the closing "Book on WhatsApp" pill is marigold with wine text; footer links turn marigold on hover; focus rings on wine and rani bands switch to marigold.

### Tertiary (the henna ramp; canvas only, plus stain numerals)
- **Paste** (`paste`): wet henna paste body, with a darker raised shadow and a cream wet sheen while fresh.
- **Fresh Stain** (`stain-fresh`): the stain the instant the paste comes off.
- **Rising Stain** (`stain-mid`): the midpoint as it deepens (at 45% of the deepen time).
- **Deep Stain** (`stain`): the settled maroon-brown. Also used in CSS for the big step numerals and the separator dots in "Where I go".

### Neutral
- **Skin** (`skin`): page ground and the scalloped cuff of every lace edge; also `theme-color`.
- **Lit Skin** (`skin-lit`): center of the radial glow behind the drawing stage only.
- **Henna Ink** (`ink`): all body and heading text on skin, and input text.
- **Soft Ink** (`ink-soft`): secondary text on skin: "by Neha", stage hint, "(optional)", helper and card sub-lines.
- **Cream** (`cream`): text on wine; field and card surfaces on skin.
- **Soft Cream** (`cream-soft`): secondary text on wine (notes, close paragraph, footer small print).
- **Error** (`error`): error messages and the border of an invalid field or chip group.
- Hairlines on wine are cream at low alpha (`rgba(251,239,230,.18)` for row rules, `.16` for the footer rule, `.5` for the arrow ring). Field and chip strokes are ink at 60% (`rgba(58,13,39,.6)`).

### Named Rules
**The Whole-Band Rule.** Color commits by section, not by accent. A section is bare skin, drenched wine, or drenched rani; never a wine card floating on skin, never a rani stripe inside a wine band.

**The Henna-Ramp Rule.** `paste`, `stain-fresh`, `stain-mid` and `stain` belong to henna marks. Outside the canvas, only `stain` appears, and only as a numeral or separator on skin. Never use the ramp for buttons or UI states.

**The Marigold-Is-Response Rule.** Marigold appears where something answers you (hover, focus on dark bands) plus the single closing call to action. It is never a section fill.

## Typography

**Display Font:** system serif stack: Iowan Old Style, Palatino Linotype, Palatino, Book Antiqua, Georgia, serif
**Body Font:** system sans stack: system-ui, -apple-system, Segoe UI, Helvetica Neue, Arial, sans-serif

**Character:** The system fonts are the owner's house rule, a decision rather than a gap: no web fonts are loaded, which keeps the page light in Facebook's in-app browser on cellular. The serif carries the brand voice in bold uppercase, like the flyer's "ROYAL"; the sans carries reading and tapping.

### Hierarchy
- **Display** (serif 700, uppercase, `clamp(2.45rem, 11.2vw, 5.4rem)`, line-height 0.96): the hero headline only, max ~9.5em wide, balanced wrap.
- **Headline** (serif 700, uppercase, `clamp(2rem, 8.6vw, 3.6rem)`, line-height 1): every section title. The closing brand-name title runs one step larger (`clamp(2.2rem, 10vw, 4.6rem)`, line-height 0.98).
- **Title** (serif 700, uppercase, 1.375rem, +0.02em): step titles and "Where I go".
- **List title** (serif 700, sentence case, 1.25rem/1.2): service rows and the place names line.
- **Wordmark** (serif 700, uppercase, 1.125rem, +0.14em tracking; 1rem/+0.1em under 380px): "ROYAL HENNA" in the header; the footer repeats it at 1.0625rem/+0.12em.
- **Aside** (serif italic 400, 0.9375rem): "by Neha" under the wordmark and the stage hint. The only italic in the system.
- **Body** (sans 400, 1.0625rem/1.55): all running copy, kept to 31-40ch; the hero promise scales `clamp(1.0625rem, 4.6vw, 1.25rem)` at 1.45.
- **Label** (sans 700, 1.0625rem/1): buttons and form legends/labels; the header phone number is sans 700 1rem with tabular numerals.
- **Small** (sans 400, 0.9375rem): helper text, notes, errors (700), card sub-lines.
- **Step numeral** (serif 700, 2.75rem, `stain`): the 1-2-3 of "How booking works".

### Named Rules
**The House Fonts Rule.** System stacks only. Headings use the system serif; body, labels and controls use the system sans. Do not load a web font.

**The Serif-Shouts Rule.** Headings h1-h3 are bold serif uppercase at line-height 1 or tighter. Sentence case serif is for list items; italic serif is only for small asides.

## Layout

Phone-first single column. Content sits in a centered wrapper (max 1180px; 1440px at 1024px+) with a gutter of 16px on phones, 32px from 720px, and `clamp(32px, 5vw, 96px)` from 1024px. Bands pad 52px top / 60px bottom on phones and 72px / 84px from 720px. Vertical rhythm inside a band steps 10, 12, 18, 20, 26px between related elements; 44px separates sub-blocks ("Where I go").

The first screen on a phone is fixed by contract: wordmark left and the 313 number top-right in the header, a three-line display headline, the promise, then two full-width stacked pill buttons (WhatsApp filled, Plan outlined, max 420px), and the drawing stage filling the bottom (`clamp(300px, 46svh, 440px)`). At 1024px the hero becomes a two-column grid (copy 1fr, stage 1.1fr) sized to the viewport minus the header (`clamp(600px, 100svh - 68px, 880px)`), buttons sit side by side, and the stage hint centers at the stage's foot.

At 720px: steps go three across, the form's date and headcount fields pair up, the service rows flow into two columns (48px gap). At 1024px the plan section adds a sticky WhatsApp-message preview column (400px) beside the 640px form.

Sections join through lace edges: 50px (56px from 720px) strips whose skin side is scalloped at a 40px pitch (48px from 720px) and carries a henna cuff the cone pipes when it scrolls into view.

### Named Rules
**The One Number Rule.** The phone number appears top-right in the header on the first screen and nowhere else above the fold. There is no sticky bar or floating action button; the header scrolls away.

## Elevation & Depth

Flat by default. Depth comes from the henna itself (the paste's raised offset shadow and wet sheen, the falling crumbs, the stage's radial skin glow) and from band color changes, not from layered surfaces. Shadows are used only under the two cream objects that sit on a colored ground, and they are soft and low.

### Shadow Vocabulary
- **Lifted cream** (`box-shadow: 0 10px 22px -12px rgba(20,4,12,.45)`): the Instagram link card on rani.
- **Lifted bubble** (`box-shadow: 0 10px 22px -14px rgba(20,4,12,.45)`): the WhatsApp preview bubble on skin.

### Named Rules
**The Paste-Has-Depth Rule.** Only henna marks get material depth (offset shadow under wet paste, cream sheen on top). UI depth stays at one soft cream lift.

## Shapes

Three corner families: full pills (999px) for every button and chip; soft 12px corners for fields and 14px for the link card; and a circle for every arrow disc (44px). Focus rings round to 6px. Section seams are scallops: half-circles of skin at a 40-48px pitch, never a straight cut or a wave. The preview bubble is the one asymmetric shape (16px with a 4px tail corner), a chat-bubble quote rather than a system shape. Ornament geometry is the four-mark grammar (line, petal, dot, scallop) drawn by hand-jittered strokes.

## Components

### Buttons
Big, round, confident, made to be thumbed.
- **Shape:** full pill (999px), 56px tall, 24px side padding (28px side-by-side on desktop), 2px border, 22px icon with a 10px gap.
- **Fill:** wine with cream text. Hover turns rani (fill and border).
- **Line:** transparent with a wine border and wine text. Hover turns border and text rani.
- **Marigold (closing CTA on wine):** marigold with wine text. Hover turns cream.
- **Press:** scales to 0.98 (off under reduced motion). Transitions 0.2s on color, 0.15s on transform.
- **Form submit:** keeps its wine fill on hover and instead gets a 2px rani outline at 3px offset, following the form-controls rule.
- **Text fallback ("No WhatsApp?"):** underlined sans 600 link-button; hover/focus turns rani with a 2px rani outline.

### Chips
- **Style:** pill, 44px tall, 16px padding, 1.5px ink-60% stroke on a 55% cream wash, sans 600.
- **State:** selected fills wine with cream text. Hover and keyboard focus add a 2px rani outline at 2px offset; the fill does not change on hover.

### Cards / Containers
- **Link card (Instagram):** cream on rani, 14px corners, 14px 20px padding, min 84px tall, 40px rani icon, sans 700 1.1875rem title over a soft-ink sub-line, wine arrow disc at the end that turns rani on hover/focus. Lifted cream shadow.
- There are no other cards; content otherwise sits directly on its band.

### Inputs / Fields
- **Style:** cream fill, 1.5px ink-60% stroke, 12px corners, 52px min height (textarea 96px, vertical resize), 12px 14px padding, body type.
- **Hover / Focus:** 2px rani outline at 1px offset and the border turns rani. Hover and focus look the same on purpose.
- **Error:** error-colored border and a bold 0.9375rem error line beneath, in first person ("Tell me the town so I can check I can get there.").
- Labels are sans 700 above the field; "(optional)" is sans 400 in soft ink.

### Navigation
- **Header:** not sticky. Wordmark (serif uppercase over italic "by Neha") at left; tap-to-call phone number with an 18px phone icon at right, sans 700 tabular, 44px tall, turns rani on hover.
- **Footer (wine):** serif wordmark, then a list of 44px-tall links in cream (marigold on hover) and plain cream-soft text items, inline from 720px. Contact lines are the call number, WhatsApp and Instagram; an email link belongs only here, and only once one exists.

### Service Row (signature)
The occasions list on wine: each row is a full-width link, serif 700 1.25rem, min 64px, cream hairline rules between rows, and a 44px circular arrow with a translucent cream ring at the end. On hover or focus only the arrow changes: it fills marigold with a wine arrow (focus adds a marigold ring). The row itself never gains a background, outline, or shadow. Each row opens WhatsApp with that occasion's message started.

### Drawing Stage (signature)
The hero canvas on a radial skin glow. A cone (brown-black body with a rani band and a cream tip) pipes a mandala by itself, then the paste dries, sweeps off in crumbs and the stain deepens orange to maroon, holds, fades, and the next of three designs begins. Touch or mouse pipes visitor paste (the cone pauses, resuming 2.5s after the last touch); the cursor is hidden because the cone is the cursor. An italic soft-ink hint ("Draw here with your finger. It's henna." / "Draw here. It's henna." on fine pointers) labels it. Timing lives in the engine's tunables: dry 2.2s, sweep 2.4s, flake 1.1s, deepen 7s, hold 9s, fade 4.5s; paste line 2.6px phone / 3.2px desktop. Reduced motion shows finished stains with no piping.

### Lace Edge (signature)
Every section seam: a scalloped skin cuff with a henna border (a rule line, a scallop chain, a dot in each scallop, and alternating small petals and dots standing on the rule), piped by the same cone at 950px/s when it scrolls into view, then dried (1.2s), swept (1.6s), stained, and kept.

## Do's and Don'ts

### Do:
- **Do** draw every ornament with the henna engine in the four-mark grammar (line, petal, dot, scallop) and let it dry and stain through the paste-to-stain ramp.
- **Do** drench whole sections in `wine` or `rani` and join them to skin with a scalloped lace edge (40px pitch phone, 48px desktop).
- **Do** set headings in the system serif, bold uppercase, and everything else in the system sans.
- **Do** keep every tap target at least 44px and primary buttons at 56px full pills.
- **Do** give every form control (field, chip, submit, text fallback) a rani outline on hover and focus-visible.
- **Do** switch focus rings to marigold on wine and rani bands; rani on skin.
- **Do** write labels, errors and helper text in Neha's first person.

### Don't:
- **Don't** load web fonts; the system stacks are the house rule.
- **Don't** show the phone number anywhere on the first screen except top-right in the header, and don't add a sticky bar or floating call button.
- **Don't** add email links, except a single footer email if one ever exists.
- **Don't** change a service row's background, text, outline or shadow on hover; only its arrow fills marigold.
- **Don't** use the stain or paste colors for UI states, and don't use marigold as a section fill.
- **Don't** use static or clip-art henna as ornament, or stock photos of other artists' work; ornament is piped live. Neha's own work photos are content and belong in the work band.
- **Don't** add layered shadows; the only lift is the soft cream shadow under a cream object on color.
