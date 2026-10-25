# Design System Generation

Use this guide in Create mode when the brief is short, incomplete, or gives no explicit visual direction. Generate a coherent recommendation from the prompt alone when possible; do not make the user complete a design questionnaire.

## 1. Read the brief for signals

Extract only what is stated or strongly implied:

- **Presentation purpose and subject:** lesson, report, proposal, update, product walkthrough, and so on.
- **Audience and knowledge level:** use explicit clues; if absent for a simple informational or educational request, default to an introductory general audience. Do not invent a grade, profession, or specialist context.
- **Outcome and delivery:** what viewers should understand, decide, or do; live, self-guided, or unknown.
- **Tone and complexity:** calm, persuasive, technical, playful, formal; simple or evidence-heavy.
- **Hard constraints:** brand kit, supplied assets, required language, accessibility needs, slide count, aspect ratio, or source limits.

Separate explicit facts from assumptions. The prompt language is a reasonable default for deck language. 

Example: If the user says “simple” without a length, use a concise deck; a short slide sequence is usually enough.

Apply other reversible production defaults as needed, and mention only assumptions that affect the result.

## 2. Decide whether to ask or proceed

Proceed with sensible defaults when the brief has a clear subject and purpose and the remaining gaps concern reversible design or presentation choices. Ask only when a missing choice could materially change the content or result, such as a mandated grade level, curriculum, exact slide limit, brand rule, source-only constraint, or high-stakes audience.

Do not resolve uncertain factual claims by styling or summarizing them as though they were verified. Follow [Research and Sourcing](research-and-sourcing.md) for factual content beyond supplied material. If a key claim cannot be verified, disclose the gap and ask whether to use only supplied sources or pause.

## 3. Generate independent design dimensions

First choose the story pattern from the presentation's purpose. Then recommend each visual dimension independently. A category or style may inform a choice, but does not lock the other dimensions.

| Dimension | Decide from | Reference |
|---|---|---|
| Story pattern | Purpose, audience question, desired outcome, and delivery | [Presentation Structures](presentation-structures/index.md); use [Reasoning Rules](reasoning-rules.md) only for a product or service walkthrough |
| Style | Purpose, audience, tone, and content character; choose one dominant direction and at most one restrained influence | Use [Style Recommendations](style-recommendations/index.md) for general presentations; consult [Product Styles](product-styles/index.md) only for product- or service-focused presentations |
| Palette | Brand values first, then mood, contrast, content meaning, and imagery; assign functional color roles | [Color Palettes](color-palettes/index.md) |
| Typography | Audience, language, reading conditions, tone, and hierarchy; keep body text easy to read | [Font and Typography Pairings](font-and-typography-pairings/index.md) |
| Imagery and diagrams | Evidence, explanation, audience familiarity, and story | [UX Guidelines](design-guideline.md) |
| Charts | The question and data being shown, with accurate labels, units, scales, and sources | [Chart Types](chart-types/index.md) |
| Effects and motion | Requested mood and whether the effect improves comprehension or orientation | [UX Guidelines](design-guideline.md) |

Do not reuse one category lookup as a complete design preset. For example, an education palette can pair with editorial, playful, or technical visual styles; a restrained palette can pair with either serif or sans-serif typography. Make the choices work together through contrast, hierarchy, and tone, not through fixed bundles.

## 4. Check compatibility

Before authoring, make a short internal design brief containing:

- inferred purpose and audience, with material assumptions identified;
- story pattern;
- selected style and a sentence describing observable characteristics;
- palette roles and values or brand colors;
- heading/body type candidates and hierarchy;
- imagery, diagram, chart, and effect treatment where relevant;
- anti-patterns that would undermine this particular brief.

Check that the palette supports legibility and meaningful data encoding, typography supports the language and reading context, and effects do not compete with the story. If recommendations conflict, preserve explicit user and brand constraints, accuracy, accessibility, and readability first; revise optional style choices second. Do not calculate a numeric score unless requested.

Verify candidate fonts and chart types in the selected platform before claiming they are available or applied. Report proposed candidates as candidates until the design or editor confirms them. For Canva-specific checks, follow [Canva Platform Guide](platforms/canva.md). Include the required Design Direction fields and pre-delivery checklist from [Design Direction](design-direction.md) in the final Create report.

## Example

Prompt: “Build me a simple presentation for the prokaryotic and eukaryotic cell.”

Reasonable inference: a concise introductory lesson for general learners, in the language of the prompt. A fitting story is a brief introduction, a look at each cell type, a side-by-side comparison, and a recap. One possible visual recommendation is a clean, diagram-led educational style. Choose a high-contrast palette independently from the palette reference and choose a readable type pairing independently from the typography reference. Use labeled cell diagrams and restrained motion only if it helps explain structures. Verify the science and do not infer a school grade or curriculum. These are recommendations, not claims about what the selected platform has applied.

