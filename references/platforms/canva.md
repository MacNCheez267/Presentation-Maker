# Canva Platform Guide

Read this reference only when the user requests Canva or the current environment exposes Canva presentation tools. It documents Canva-specific execution details; use the universal workflow and design references for everything else. Tool names, UI controls, account capabilities, and approval requirements can change, so inspect the tools available for the current task rather than assuming a capability exists.

## Select capabilities and verify results

- Inspect the current Canva tool descriptions. Choose a tool only for a capability it explicitly supports, and follow its input, permission, approval, continuation, and wait requirements.
- Do not assume that an account has a feature, template, font, chart, export option, or permission just because Canva documents it. Confirm availability in the current tool or editor.
- If Canva is unavailable, disabled by account policy, or lacks a needed capability, state that plainly. Do not bypass account restrictions, impersonate an administrator, or claim success. Offer another available output workflow only when it would still meet the user's intent; ask if switching platforms would materially change the result.
- For asynchronous work, follow the Canva tool's continuation instructions. If a tool or UI is already waiting for the job, do not launch duplicate polling.

## Canva modes

- **Create:** use an available Canva presentation-creation capability. Apply the universal [Design System Generation](../design-system-generation.md) and design references. Verify the returned design or preview before claiming that fonts, colors, layouts, images, effects, or charts were applied.
- **Template:** identify whether the user means a reusable Brand Template or an existing presentation to use as a starting point. Resolve the exact template or design with an available search or link workflow. Create a copy when requested; otherwise preserve the original source.
- **Edit:** locate the exact presentation from the provided link, name, or a targeted search. If results are ambiguous, present the plausible matches and ask which one. Make only requested edits; preview a draft when supported and follow Canva's required approval before committing.
- **Review:** inspect without editing. If available tools do not reveal enough of the presentation, report the limits and only findings supported by visible content.

Do not publish, share, or change access unless the user requests it and the available tool supports it. Follow all tool-required confirmation steps before saving or committing a design.

## Fonts and charts

- Treat font names in [Font and Typography Pairings](../font-and-typography-pairings/index.md) as candidates. Check the current font picker or Brand Kit before claiming a font is available or applied. Uploaded fonts and account capabilities can vary. If unavailable, verify a close substitute in the current environment and disclose the change.
- Treat [Chart Types](../chart-types/index.md) as platform-independent guidance, not a promise about Canva's current menu. Confirm the exact native chart type in Canva's current chart picker before claiming native editability. Do not describe a manually assembled diagram as a native chart.
- Official help references for current Canva-specific details:
  - [Choose chart types](https://www.canva.com/help/chart-types/)
  - [Compare parts of a whole with pie and donut charts](https://www.canva.com/help/pie-and-donut-charts/)
  - [Get started with Canva Charts](https://www.canva.com/help/charts/)
  - [Set up and use Brand Fonts](https://www.canva.com/help/brand-fonts/)

## Preview and delivery

When Canva provides a preview or readable design content, compare it with the brief, supplied sources, and intended audience. Check story coverage, factual support, legibility, clipping, visual consistency, and charts when visible. Correct issues only when the available editing workflow supports it. Do not describe unseen slides or mark an uninspectable check as passed.

Report a Canva design link, preview, or export only when the tool confirms it. In the final response, identify what was created, edited, or reviewed, include a concise design direction for Create mode, and state material tool or preview limitations. Never imply a Canva operation succeeded when it failed or returned no confirming result.