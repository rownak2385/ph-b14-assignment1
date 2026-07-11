# AI Challenge Documentation

## Tool Used
OpenAI Codex

## Section Name
Beyond the Stage

## Purpose
This section introduces interactive DevConf experiences beyond regular talks, showing that attendees can build prototypes, make focused connections, and explore live technology demos.

## Initial Prompt

```text
Continue the existing DEVCONF 2026 project.

STEP 6: Replace the AI Challenge placeholder with an original section called “Beyond the Stage.”

This is the officially AI-assisted section of the assignment.

Preserve all existing navbar, hero, speakers, pricing, and footer code.

SECTION PURPOSE

Show that DevConf 2026 includes interactive experiences beyond regular conference talks.

SECTION CONTENT

Eyebrow:
MORE THAN TALKS

Heading:
Beyond the Stage

Supporting paragraph:
Turn ideas into prototypes, meet people building the next big thing, and experience technology in motion.

Create three unique experience cards.

CARD 1

Label:
BUILD

Title:
Live Code Lab

Description:
Pair with experienced engineers and transform a challenge into a working prototype during a guided 90-minute build session.

Detail:
12 guided labs

CARD 2

Label:
CONNECT

Title:
Founder Matchroom

Description:
Meet founders, product thinkers, designers, and developers through focused small-group collaboration sessions.

Detail:
Curated networking

CARD 3

Label:
DISCOVER

Title:
Demo Arena

Description:
Watch emerging tools, open-source experiments, and early-stage products demonstrated live by their creators.

Detail:
30 live demos

CTA:
Explore the Experience

The CTA can link to the section itself or to a relevant internal destination. Do not invent JavaScript functionality.

VISUAL REQUIREMENTS

Design the section to fit naturally between pricing and the footer.

Use:

- Dark navy section background
- Centered white heading
- Muted light supporting text
- Bright blue accent elements
- Three cards in one row on desktop
- Light or subtly transparent card backgrounds
- Thin borders
- Small rounded corners
- Generous spacing
- Restrained CSS-only hover effects
- A centered blue CTA below the cards

Do not use the purple placeholder styling in the finished design. Purple belongs only to the original placeholder and does not match the final page.

CARD VISUAL IDEA

Each card may include:

- A CSS-created number such as 01, 02, and 03
- A small uppercase category label
- An abstract CSS decoration
- A title
- Description
- Detail row

Do not use an external icon library.

RESPONSIVE REQUIREMENTS

- Three cards in one row on desktop
- Two columns only if the tablet layout remains balanced
- One card per row on mobile
- No horizontal overflow
- CTA remains centered
- Padding reduces appropriately on smaller screens

ACCESSIBILITY

- Use a semantic section
- Use article elements for cards
- Maintain logical heading order
- Add visible focus styles
- Respect prefers-reduced-motion
- Ensure readable color contrast
- Do not use color alone to communicate meaning

COMMENTING REQUIREMENTS

Add clear HTML and CSS comments explaining:

- The AI-assisted section boundary
- Card grid
- CSS decorative elements
- Hover interaction
- Reduced-motion behaviour
- Responsive stacking

Keep the code beginner-friendly and well organized.

PROMPTS.MD

Update PROMPTS.md with:

# AI Challenge Documentation

## Tool Used
OpenAI Codex

## Section Name
Beyond the Stage

## Purpose
Explain briefly that the section introduces interactive DevConf experiences beyond regular talks.

## Initial Prompt
Insert the complete Step 6 prompt verbatim.

## How AI Was Used
State that AI helped with concept development, content organization, responsive layout, semantic HTML, and initial CSS styling.

## Manual Adjustments
Add a checklist placeholder where I can later record my own changes.

Do not place the prompts from Steps 1–5 into PROMPTS.md.

At the end:

- Summarize the section
- Explain its responsive behaviour
- List accessibility decisions
- Suggest this commit message:

feat: add AI-assisted beyond the stage section
```

## How AI Was Used
AI helped with concept development, content organization, responsive layout planning, semantic HTML structure, and initial CSS styling for the Beyond the Stage section.

## Manual Adjustments

- [ ] Review the section visually against the assignment screenshot.
- [ ] Adjust spacing, colors, or wording if needed.
- [ ] Test desktop, tablet, and mobile layouts.
- [ ] Confirm the final GitHub Pages deployment works.
