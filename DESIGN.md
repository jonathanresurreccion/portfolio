---
name: Jonathan Jed Resurreccion, Field Book
description: A civil engineer's record booked like a surveyor's level book, every claim on a ruled line beside a red margin, pointing to its proof.
colors:
  cover-yellow: "#F2C200"
  cover-ink-soft: "#3D3500"
  paper: "#FBFBF8"
  label-white: "#FFFFFF"
  rule: "#D3E0DA"
  rule-strong: "#A9C0B7"
  margin-red: "#C8372D"
  ink: "#17191B"
  ink-soft: "#3B4043"
  muted: "#5D6468"
  pen-blue: "#1F4BA0"
  night: "#121416"
  night-line: "#2A2E32"
  night-muted: "#A3A9AE"
typography:
  display:
    fontFamily: "Archivo, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(3.25rem, 1.6rem + 6.6vw, 6rem)"
    fontWeight: 800
    lineHeight: 0.9
    letterSpacing: "-0.03em"
    fontVariation: "'wdth' 82"
  headline:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(2.25rem, 1.6rem + 2.6vw, 3.5rem)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.025em"
    fontVariation: "'wdth' 82"
  title:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.375rem, 1.2rem + 0.75vw, 1.75rem)"
    fontWeight: 700
    lineHeight: 1.18
    letterSpacing: "-0.015em"
  lead:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.125rem, 1.05rem + 0.35vw, 1.3125rem)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
    fontFeature: "'tnum' 1, 'lnum' 1"
  small:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "0.08em"
rounded:
  none: "0px"
spacing:
  photo-gap: "0.5rem"
  control-gap: "0.75rem"
  doc-gap: "1rem"
  gap: "2.5rem"
  margin-column: "9.5rem"
  row: "clamp(2.25rem, 3.5vw, 3rem)"
  section: "clamp(4.5rem, 3rem + 5vw, 7.5rem)"
  gutter: "clamp(1.25rem, 4vw, 3rem)"
  content-max: "1180px"
components:
  button-solid:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.cover-yellow}"
    typography: "{typography.small}"
    rounded: "{rounded.none}"
    padding: "0 1.5rem"
    height: "52px"
  button-solid-hover:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.small}"
    rounded: "{rounded.none}"
    padding: "0 1.5rem"
    height: "52px"
  button-line-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.cover-yellow}"
  proof-link:
    textColor: "{colors.pen-blue}"
    typography: "{typography.small}"
  stamp:
    backgroundColor: "transparent"
    textColor: "{colors.margin-red}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0.3rem 0.5rem"
  cover-label:
    backgroundColor: "{colors.label-white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "0.875rem 1.25rem 1rem"
  lightbox:
    backgroundColor: "{colors.night}"
    textColor: "{colors.label-white}"
  lightbox-button:
    backgroundColor: "{colors.night}"
    textColor: "{colors.label-white}"
    size: "44px"
  lightbox-button-hover:
    backgroundColor: "{colors.cover-yellow}"
    textColor: "{colors.ink}"
---

# Design System: Jonathan Jed Resurreccion, Field Book

## Overview

**Creative North Star: "The Surveyor's Level Book"**

The page is a field book. A yellow weather cover opens and closes it; between the covers are cool white pages ruled with pale green-blue lines, and one continuous red margin rule runs down the whole interior. Dates and periods are booked to the left of that rule, entries to the right. Every claim is a booked entry, and the claim that has a document behind it carries a pen-blue link that opens that exact document. The reader should feel they are checking a record, not being sold to.

Density is that of a working notebook: generous vertical rhythm between entries, tight hairline rulings inside them, specs set as two-column field/value rows. There is one typeface, Archivo, with its width axis doing the work a second face would normally do: headings are heavy and narrowed to 82%, everything else sits at normal width. Figures are tabular and lining everywhere, because the content is dates, values and quantities.

The world is flat paper and ink. Depth exists in exactly one place: the site photo tipped onto the cover with a white border, a slight rotation and a soft cast shadow. It rejects the generic SaaS portfolio: split hero with gradient, stat cards, monospace labels on cream.

**Key Characteristics:**
- Yellow cover / white ruled pages / yellow back cover, in that order.
- One red margin rule, continuous through every interior section, with dates booked to its left.
- Square corners everywhere; borders and rulings, never cards with shadows.
- Pen blue is reserved for proof links; red is reserved for the margin, the current-entry dot and outlined stamps.
- One typeface (Archivo variable), narrowed for headings, tabular figures throughout.
- One entrance motion: the cover photo settles.

## Colors

Two loud field colors (cover yellow, margin red) held in place by a cool, quiet paper-and-ink base, with a single functional blue.

### Primary
- **Weather-Cover Yellow** (cover-yellow): owns the opening cover and the closing contact back cover as full-bleed fields, and nothing else on paper. It reappears as the text color of solid ink buttons, as text selection, and as the hover/active color inside the dark lightbox.

### Secondary
- **Margin Red** (margin-red): the 2px continuous margin rule down the interior pages, the 12px dot marking the current (active) entry, the active nav underline, and the outline and text of stamps.

### Tertiary
- **Pen Blue** (pen-blue): proof links only (inline buttons that open a document gallery), the hover title of a document thumbnail, and the default focus outline on paper.

### Neutral
- **Field Ink** (ink): all headings, values, solid button fill, cover-label border and cover rulings.
- **Soft Ink** (ink-soft): body and lead paragraphs on paper.
- **Cover Ink Soft** (cover-ink-soft): secondary text on yellow (lead, role separators, captions); a dark olive that keeps contrast on yellow without going grey.
- **Muted Graphite** (muted): field labels, small print, meta text such as dates' sub-lines and document counts.
- **Cool Paper** (paper): page background for all interior sections, the mobile menu, and the knockout ring around the current-entry dot.
- **Label White** (label-white): the printed cover label, the availability card on the back cover, document thumbnail mats, and the photo tip-in border.
- **Ruling Green-Blue** (rule): hairline rulings between entries, spec rows, facts, skills and credentials; also the placeholder fill behind photos.
- **Strong Ruling** (rule-strong): section dividers between pages, document thumbnail borders, bullet dashes, the scrolled nav's bottom rule.
- **Night** (night), **Night Line** (night-line), **Night Muted** (night-muted): the lightbox only. The night palette never appears on the page itself.

### Named Rules
**The Two Covers Rule.** Yellow is a cover, not an accent. It fills the first and last blocks edge to edge; inside the pages it never appears as a fill, badge or highlight.

**The Pen Means Proof Rule.** Pen blue marks a link to evidence. If an element is blue, clicking it opens a document or photo that backs the sentence it sits in. Navigation, contact and CV links stay ink.

**The Red Is Ruled Rule.** Red draws the margin and certifies facts. It is never used for text emphasis, errors, or decorative fills.

## Typography

**Display Font:** Archivo (variable, weight 100 to 900, width 62% to 125%), with ui-sans-serif / system-ui fallback
**Body Font:** Archivo, same file
**Label/Mono Font:** none; labels are Archivo uppercase

**Character:** One engineering grotesque used at two widths. Narrowed and heavy for headings, it reads like stencilled lettering on a site board; at normal width it is a plain, legible record hand.

### Hierarchy
- **Display** (800, clamp 3.25rem to 6rem, 0.9, width 82%): the name on the cover only. Capped at 6rem.
- **Headline** (800, clamp 2.25rem to 3.5rem, 1.0, width 82%, balanced wrap): one per page section, booked on the right of the margin.
- **Title** (700, clamp 1.375rem to 1.75rem, 1.18, balanced wrap): entry titles (employer / project) and card titles.
- **Subtitle** (600, 1.0625rem, 1.35): block headers within an entry (photo strips, document sets), paired with a muted count on the right.
- **Lead** (400, clamp 1.125rem to 1.3125rem, 1.5, max 38em): section intros and the cover lead; also the roles line on the cover at 600.
- **Body** (400, 1.0625rem, 1.65, max 40em; bullets max 44em): paragraphs and bulleted claims.
- **Small** (400, 0.875rem, 1.55, muted): meta lines, dates, captions, button text (at 600).
- **Label** (600, 0.75rem, 0.08em tracking, uppercase, muted): the field names in field/value rows (Role, Status, Sector, Licence). Stamps share this size at 700 in red.

### Named Rules
**The One Hand Rule.** Archivo is the only typeface. Hierarchy comes from weight and the width axis (82% for display and headline), never from a second family or a monospace.

**The Booked Figures Rule.** Tabular, lining figures are set on body (`font-variant-numeric: tabular-nums lining-nums`) so dates, values and phone numbers align like a ledger.

**The Field Name Rule.** Uppercase tracked labels name a field in a field/value pair (a dt, or the contact type in a contact row). They are never placed above a heading as a kicker.

## Layout

The page is a single column of sections inside a 1180px content measure with a fluid gutter (1.25rem to 3rem). Interior sections are laid on a two-column "line" grid: a 9.5rem margin column for dates, a 2.5rem gap, then the body column. The red margin rule is drawn once, as an absolutely positioned 2px line on the pages wrapper, aligned to the right edge of the margin column, so it runs unbroken through every interior section.

Vertical rhythm: sections are padded by a fluid section step (4.5rem to 7.5rem) and separated by a strong ruling; entries are padded by a row step (2.25rem to 3rem) with a hairline ruling above each and below the last. Inside entries, field/value specs sit in a two-column grid of ruled rows (6.5rem label column); facts and tool lists use a 9rem label column.

Cover: a 7fr / 5fr grid, text left and the tipped-in photo right, followed by a six-cell printed label (3 columns by 2 rows) that sits inside a 1440x900 first view. Back cover: 6fr / 5fr, contact rows left, white availability card right.

Responsive behavior:
- At 1100px the margin column narrows to 8rem and the gap to 2rem; document grids go from 4 to 2 columns.
- At 980px the nav collapses to a menu button; the cover and back cover stack; the cover label goes to 2 columns; specs go to 1 column.
- At 760px the margin column collapses to zero: the red rule moves to the gutter's edge, dates book above their entry left-aligned, and the current-entry dot sits on the rule.
- At 560px the cover label goes to 1 column, cover buttons go full width, and the first photo in a strip takes a full row.

## Elevation & Depth

The system is flat. Depth is conveyed by rulings, borders and the contrast between yellow cover, white label and cool paper. There is one lifted object: the cover photo, which is a print tipped onto the cover. The fixed nav, once scrolled onto the paper, becomes a near-opaque paper bar with a backdrop blur and a single 1px strong-ruling line beneath it; that line is drawn with a zero-blur box-shadow and is a rule, not elevation.

### Shadow Vocabulary
- **Tip-in cast** (`box-shadow: 0 22px 40px -18px rgba(40,30,0,.55), 0 2px 6px rgba(40,30,0,.2)`): the cover photo only, with a warm cast so it reads as lying on yellow.

### Named Rules
**The One Print Rule.** Only the tipped-in cover photo casts a shadow. Cards, buttons, thumbnails and dialogs do not.

## Shapes

Square corners throughout (0px radius). The single round form is the 12px current-entry dot on the margin rule. Borders carry the form language: 2px ink for buttons, the cover label, the availability card and cover rulings; 1.5px red for stamps; 1px strong ruling for document thumbnails; 1px pale ruling between rows. The tipped-in photo is the only rotated element (1.25deg) and the only element with a thick white mat (10px).

## Components

### Buttons
Square, bordered and blunt, like printed tabs.
- **Shape:** square (0px), 2px ink border, 52px minimum height (40px in the nav).
- **Solid:** ink fill with cover-yellow text, 0 1.5rem padding, small type at 600, 0.02em tracking, optional 18px stroke icon trailing.
- **Line:** transparent with ink text and ink border.
- **Hover / Focus:** solid and line swap (solid empties to ink-on-transparent; line fills ink with yellow text), 0.2s on the house ease. Focus is a 2px outline offset 3px, pen blue on paper and ink on the covers.
- Buttons appear in pairs (Email me, Download CV) on the covers and singly in the nav.

### Proof Links (signature)
- **Style:** inline buttons inside a bulleted claim, pen blue, 600, small type, underlined 1px at 0.22em offset, with a 15px document or photo stroke icon. Hover thickens the underline to 2px.
- **Behavior:** each opens the matching gallery in the lightbox dialog. They sit at the end of the sentence they prove.

### Stamps
- **Style:** outlined red, 1.5px border, label size at 700, uppercase, 0.08em tracking, 0.3rem by 0.5rem padding, no fill.
- **Use:** certified facts only (Licensed, Assessed, Project-in-Charge, RFTI certified), right-aligned on a credential row or set in a small group under an entry title.

### Cover Label
- **Style:** a printed form: white fill, 2px ink border, 3 by 2 grid of cells divided by 1px ink lines; each cell is a field label over a value with the key phrase in bold body size.

### Entries and Field Rows
- **Entry:** a line grid with the date in the margin (600, small, sub-line muted) and title, meta, specs, bullets and evidence blocks in the body column, ruled above and below.
- **Specs / Facts:** ruled field/value rows, uppercase label left, value in ink right.
- **Bullets:** a 0.625rem by 2px strong-ruling dash instead of a dot.

### Evidence Blocks
- **Photo strip:** a flex row of photos sized by their aspect ratio (`--r`), 0.5rem gap, cropped, ruling-colored placeholder; hover scales the image to 1.04.
- **Document thumbnails:** 4/3 crops anchored to the top of the page, white mat, 1px strong-ruling border that darkens to ink on hover, title and page count below; the title turns pen blue and underlined on hover.

### Navigation
- **Style:** fixed 64px bar, transparent over the cover, paper with blur and a strong-ruling underline over the pages. Brand at 800 small, links at 500 small with a 2px underline: current color on hover, margin red for the active section.
- **Mobile:** a 44px bordered menu button with three ink bars that cross on open; the menu drops as a paper panel with ruled rows at lead size and a full-width solid CV button.

### Contact Rows
- **Style:** on the yellow back cover, ruled rows (2px ink top, 1px ink between) of field label, value at lead size 700, and a 20px arrow that nudges up-right on hover while the value underlines.

### Lightbox
- **Style:** a full-screen night dialog: top bar with count and title, contained image stage, caption, and a thumbnail strip. 44px square controls with night-line borders turn cover yellow on hover; the current thumbnail gets a yellow border. Opens with a 0.25s fade; images fade in on load.

## Do's and Don'ts

### Do:
- **Do** book every dated item on the line grid with its date to the left of the red margin rule (9.5rem column at desktop).
- **Do** keep yellow for the full-bleed opening and closing covers, and white label cards that sit on them.
- **Do** attach a pen-blue proof link to any claim that has a document or photo behind it, at the end of that claim.
- **Do** use outlined red stamps for certified facts (licences, assessments, certifications, roles of record).
- **Do** set headings in Archivo at 800 and 82% width; set everything else at normal width.
- **Do** separate rows with 1px pale rulings and sections with 1px strong rulings, rather than cards.
- **Do** keep every corner square.

### Don't:
- **Don't** introduce a second typeface or any monospace.
- **Don't** use gradients.
- **Don't** add shadows to anything but the tipped-in cover photo.
- **Don't** use pen blue for navigation, contact or CV links; blue means proof.
- **Don't** put an uppercase label above a heading as a kicker; uppercase labels only name fields.
- **Don't** build split heroes, stat cards, or monospace labels on cream.
- **Don't** add entrance animations beyond the cover photo settling; state transitions (hover, dialog fade) are fine.
