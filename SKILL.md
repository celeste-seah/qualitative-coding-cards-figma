---
name: qualitative-coding-cards-figma
description: First Cycle qualitative coding of mixed research evidence into collocated Figma cards, run by Figma's built-in AI inside the Figma file. Use when coding from within Figma itself. For the Claude Code + Figma MCP version, where Claude does the coding, use qualitative-coding-cards instead.
---

# Qualitative Coding Cards (Figma-native)

Original version of this workflow, written for Figma's in-app AI. The Claude Code version lives in the sibling `qualitative-coding-cards` skill.

Use this workflow to code qualitative research arranged in participant sections containing transcripts, worksheets or artifacts, and observer notes. Treat all sources in a participant section as one evidence set rather than separate datasets.

## Align before coding

1. Inspect the selected participant section and its surrounding page/activity structure.
2. Confirm the coding lenses. Default for this workflow:
   - Descriptive
   - Values
   - Emotion
   - In Vivo
3. Confirm metadata mapping. Unless directed otherwise:
   - Session comes from the page title, shortened to its session identifier.
   - Activity comes from the containing activity section, shortened to its activity identifier.
   - Participant comes from the participant section title.
4. Code one participant as a pilot and pause for review before continuing.

## Coding rules

- Segment by meaningful incident, not by speaker turn or fixed text length.
- Read transcript, worksheet/artifact, and observer notes together.
- Code substantive contributions from every speaker. Skip acknowledgments and facilitator prompts that add no analytical meaning.
- One card represents one code from one lens.
- Apply only lenses relevant to the incident. Never force every lens onto every incident.
- Avoid overcoding:
  - Do not create multiple cards that restate the same idea.
  - Prefer the most analytically useful code when Descriptive, Values, Emotion, and In Vivo alternatives substantially overlap.
  - Do not duplicate a code merely because the same idea appears in multiple sources.
- In Vivo codes must preserve the speaker’s exact wording.
- Values codes capture values, attitudes, or beliefs.
- Emotion codes require evidence of an expressed or clearly indicated emotion; do not infer unnecessarily.
- Reuse consistent code wording across participants when meanings match.
- Flag ambiguity rather than over-interpreting.

## Card format

Each card must be a standalone, independently movable frame.

Visible content, in order:

1. The code only, as the primary text. Underline it and hyperlink it to the card's own frame node, so a copy of the card made during Second Cycle work links back to the original sitting beside its evidence.
2. Metadata on a separate line in this exact format:
   `[Session | Activity | Participant]`
3. A small coding-lens label.

Do not display evidence descriptions, source locators, timestamps, or speaker details unless explicitly requested.

Name the card layer:

`[Session | Activity | Participant] Code`

When possible, retain retrievable metadata for:

- lens
- code
- session
- activity
- participant
- source type
- source locator or timestamp
- evidence speaker
- supporting evidence

## Visual treatment

- Assign one consistent color to each participant.
- Do not color cards by coding lens.
- Use the same participant color across every activity and source.
- Keep cards compact and readable.

## Placement

- Collocate cards with their evidence.
- Transcript cards should overlap the edge of the transcript near the relevant utterance.
- Worksheet/artifact cards should sit on or overlap the edge of the relevant artifact.
- Observer-note cards should sit beside or overlap the relevant note.
- Group cards from the same incident tightly together.
- Cards may overlap source material when useful, but must not overlap other cards or hide the essential evidence.
- Do not create a detached coding lane or separate coding area.

## Review

Before finishing the pilot, verify that:

- Every retained card adds distinct analytical value.
- Redundant cards have been removed.
- Codes remain close to the correct evidence.
- Metadata is separate from the code text.
- The code text on every card links to that card's own frame, not to the evidence or another card.
- Participant colors are consistent.
- Cards can be individually selected and moved for manual Second Cycle work.

This workflow performs First Cycle coding only. Leave categorization, thematic grouping, reconciliation, and Second Cycle analysis for manual follow-up unless separately requested.
