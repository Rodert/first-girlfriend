---
name: first-girlfriend
description: Create nostalgic, candid image-generation prompts of adult women and everyday moments that feel like a remembered first love. Use for first-love memories, natural girlfriend-style snapshots, relationship-distance photography, or era-specific nostalgic portraits; not for glamour, sexualized, or age-ambiguous imagery.
---

# First Girlfriend

Create a ready-to-use English image-generation prompt for a candid photograph that feels like a warm, imperfect memory of an adult woman. The result is about a relationship to a moment, not an idealized appearance.

## Core Direction

Prioritize naturalness, youthfulness without age ambiguity, everyday life, emotional distance, memory, and imperfection.

- The subject is always an adult woman. Say `adult woman`, `young adult woman`, or use unambiguously adult context. Do not use schoolgirl, teen, minor, or sexualized framing.
- Make the setting ordinary and specific: a bus stop, library window, convenience store, train seat, neighborhood street, or cafe table.
- Treat the camera as part of the story. "Someone who secretly likes her" means a respectful, consensual emotional point of view, never covert observation.
- Favor minimal makeup, normal clothing, natural skin texture, small expressions, and a candid or lightly acknowledged camera.
- Use imperfections selectively: a loose strand of hair, missed focus point, modest highlight clipping, off-center framing, or gentle motion blur. Do not stack defects until the image looks damaged.
- Avoid fashion-editorial posing, luxury signals, plastic skin, studio light, exaggerated proportions, and heavy cinematic grading unless the user asks for deliberate contrast.

## Build The Prompt

Infer unspecified choices from the user's scene. Ask one concise question only when the subject, setting, or requested output would materially change the result.

1. Establish an adult subject, everyday action, season, time, and location.
2. Choose ordinary clothing that fits the weather and location.
3. Set the subject's subtle interaction with the camera from `distance`.
4. Add two or three observed details, including at most one or two imperfections.
5. Add natural light and a casual composition.
6. Translate `era` into image-capture characteristics.
7. End with a short quality guardrail: realistic skin texture, ordinary environment, candid snapshot, no glamour retouching.

Return one polished English prompt in a code block and a compact `Choices:` line naming the inferred or selected scene, distance, and era. Provide a short negative prompt only when the image tool supports it or the user requests one. Do not add generic camera jargon merely to make the output longer.

## Controls

Honor explicit controls anywhere in the user's request. Default to `present` and choose the closest scene and distance when omitted.

### `distance`

| Value | Camera relationship |
| --- | --- |
| `stranger` | Respectful public distance; no implied intimacy. |
| `crush` | Tentative; she may notice the camera with a shy half-smile. |
| `first-date` | Slightly nervous warmth; hands and posture are not quite settled. |
| `girlfriend` | Familiar acknowledgment; she is comfortable being photographed. |
| `long-distance` | Tender attention with space or a travel/transit cue. |
| `breakup` | Quiet separation and restraint, not melodrama or distress. |
| `years-later` | Recovered-memory feeling; the past is warm but emotionally distant. |

### `era`

| Value | Capture cues |
| --- | --- |
| `2005` | Compact CCD snapshot, direct flash when appropriate, compressed color, slight highlight clipping. |
| `2010` | Early compact camera or smartphone, soft digital noise, imperfect white balance, casual album-photo feel. |
| `2015` | Early smartphone snapshot, modest dynamic range, informal social-photo framing. |
| `present` | Modern phone photo, natural detail held back from looking polished or editorial. |

Do not add fake dates, watermarks, interface overlays, or brand logos unless requested.

## Scene References

Read only the relevant palette. Preserve user-supplied details rather than replacing them with stock motifs.

- [After school / library](prompts/school.md)
- [First date](prompts/date.md)
- [Summer](prompts/summer.md)
- [Winter](prompts/winter.md)
- [Travel](prompts/travel.md)
- [Phone snapshot](prompts/candid.md)
- [Years later](prompts/years-later.md)

## Safety And Consent

Keep subjects clearly adult and public scenes dignified. Decline or redirect requests that sexualize young-looking or underage people, depict non-consensual voyeurism, or request real-person intimate imagery. Offer a clearly adult, consensual, non-identifying fictional alternative when appropriate.
