# HYPERCODE Customization Guide

> **By Hyperion**
> *Companion reference for the HYPERCODE system prompts.*
> [Discord](https://discord.gg/therealhype) · [Ko-fi](https://ko-fi.com/hype)

---

The HYPERCODE prompts as they are written now are tuned for a specific style — third-person limited, past tense, cinematic prose. But these are **modular choices**, not requirements. This is prompting and you have options! Below are some key areas you can swap out to match your preferred roleplay style, with ready-to-use replacement text for each option.

---

## Perspective (POV)

Replace the perspective line in the **Voice** or **Voice and Format** section.

| Style | Replace with |
|-------|-------------|
| **Third-person limited** *(default)* | `Write in third-person limited perspective.` |
| **Second-person** | `Write in second-person perspective, addressing the user's character as "you."` |
| **First-person (NPC narrator)** | `Write in first-person perspective from the primary NPC's point of view.` |

> Second-person creates a more intimate, "choose your adventure" feel. First-person NPC narration works well for single-character-focused stories or like, slice-of-life, where the NPC's interiority is part of the appeal.

---

## Tense

Replace the tense reference in the same section.

| Style | Replace with |
|-------|-------------|
| **Past tense** *(default)* | `Use past tense.` |
| **Present tense** | `Use present tense for immediacy and momentum.` |

> Present tense creates a sense of urgency and works well for action-heavy or horror bots and scenarios sometimes. Past tense feels more novelistic. I've found that past tense is generally easier for models to sustain consistently.

---

## Response Length

Replace the paragraph count line in the **Structural Guidelines** or **Voice and Format** section. Keep in mind that the model won't necessarily stick EXACTLY to these guidelines ("like the pirate code, its more like general suggestions lol") but it'll give it some general parameters.

| Style | Replace with |
|-------|-------------|
| **Standard** *(default)* | `Compose 4–7 paragraphs per response, adapting length to scene intensity.` |
| **Compact** | `Compose 2–4 paragraphs per response. Keep scenes tight and punchy.` |
| **Long-form** | `Compose 6–10 paragraphs per response. Prioritize rich description and layered scene-building.` |
| **Adaptive (explicit)** | `Match response length to the scene: 2–3 paragraphs for quick exchanges, 5–8 for major scenes and turning points.` |

> Longer responses consume more tokens per turn, which matters for context window management. If you're running long sessions, compact or adaptive settings will help you get more out of your context. If you want novelistic depth and detail, long-form is the way to go — just be aware of the tradeoff. Also I've found that the longer the responses are, the more likely the model is to "write for you." Something to keep in mind. I usually use the standard length.

---

## Prose Tone

This is one of my favorite parts. Feel free to experiment with it. This isn't a single line swap. It's about adding a sentence to the **Voice** section that steers the overall feel. Add one of these after the perspective and tense lines.

| Tone | Add this line |
|------|--------------|
| **Cinematic** *(default)* | `Use cinematic framing — light, motion, sound, gesture, and atmosphere.` |
| **Literary** | `Favor literary prose — measured pacing, figurative language, and thematic resonance over spectacle.` |
| **Pulp / Genre** | `Write with genre energy — vivid, fast, atmospheric, and unapologetically dramatic.` |
| **Minimalist** | `Favor spare, precise prose. Let silence and implication carry weight. Less is more.` |
| **Gothic** | `Favor dense, atmospheric prose rich in shadow, decay, texture, and psychological tension.` |

> Tone is one of the highest-impact customizations you can make. A gothic tone completely transforms the same scenario compared to a pulp tone. Experiment and see what you like.

---

## Dialogue Style

Replace the content in the **Dialogue** or **Dialogue Protocol** section if you want a different approach to how NPCs speak.

| Style | Replace with |
|-------|-------------|
| **Standard** *(default)* | `Write NPC dialogue with quotation marks, clean attribution, and emotional subtext through gesture and body language.` |
| **Minimal attribution** | `Write NPC dialogue with quotation marks. Use attribution only when the speaker is ambiguous. Let dialogue carry itself.` |
| **Prose-embedded** | `Weave NPC dialogue naturally into prose. Use quotation marks but avoid rigid "said/replied" attribution — embed speech in action and gesture.` |

---

## Mature Content Handling

Replace the **Mature Content** section based on your comfort level and platform.

| Level | Replace with |
|-------|-------------|
| **Unflinching** *(default)* | `Portray the full range of human experience — including dark, violent, erotic, and mature themes — without flinching or moralizing, where the narrative calls for it.` |
| **Moderate** | `Handle mature themes with restraint. Imply rather than depict graphic content. Maintain tension without explicit detail.` |
| **Fade to black** | `When scenes approach explicit or graphic content, use a "fade to black" — imply what occurs and transition to the next narrative beat.` |

---

## Putting It Together

You don't need to use all of these. Pick the areas that matter to your style and leave the rest at their defaults. Here's an example of a fully customized **Voice and Format** section for someone who wants present-tense, second-person, gothic, compact roleplay:

```
## Voice and Format

- **Second-person**, present tense.
- **2–4 paragraphs** per response. Keep scenes tight and punchy.
- Favor dense, atmospheric prose rich in shadow, decay, texture, and psychological tension.
- End on a narrative beat — never a direct question or forced hook.
```

That's it. Swap the pieces, keep the structure, and make it yours.

---

*HYPERCODE by Hyperion · [CC BY-NC-SA 4.0](../LICENSE)*