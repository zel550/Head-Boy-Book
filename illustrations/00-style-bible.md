# WENDELL ROLLS — Illustration Style Bible & Prompt Notes

## Tool clarification (read first)

ChatGPT's built-in image generator is **GPT Image** (currently GPT Image 2 as of April 2026) — OpenAI's own model, native to ChatGPT. OpenAI retired the **DALL·E** brand entirely in March 2025, so if you've seen references to DALL·E, that's the old name for what's now GPT Image.

**"Nano Banana" / "Nano Banana Pro" is a different product from a different company** — it's the nickname for Google's Gemini 3 Pro Image model, accessed through Gemini/Google AI Studio, not through ChatGPT. ChatGPT does not use Nano Banana. If you only use one tool, use ChatGPT/GPT Image — the consistency workflow below depends on staying in one continuous tool and conversation thread. Consider Nano Banana Pro only as a supplementary tool for one or two high-stakes assets (the cover, a large print spread) where its native 4K output and grounded-detail accuracy would matter more than workflow consistency.

## Visual style: woodcut/linocut Americana

Bold black linework, limited palette — **bone-white, lamp-black, and one accent color** (rust-red or indigo; pick one and never vary it) — visible carving texture, thick black panel border, single hard light source per image (no soft gradients). Think old almanac woodcuts, WPA-era prints, Southern folk-art broadsides.

This solves the book's hardest visual problem directly: rendering a torso unfolding out of a neck-stump as *literal anatomy* would fight the prose's own tenderness and tip into shock/body-horror imagery the book isn't going for. Woodcut renders it as **symbol** — a stalk, a root-form, a plant breaking ground — which is exactly how the prose already describes it ("It came out of him the way a plant comes out of the ground"). Reserve finer Gorey-esque pen-and-ink crosshatching, same palette, as a secondary register for close emotional beats (faces, a single expression) where the woodcut's abstraction would lose something essential.

## Consistency workflow for 24 images, done solo

1. **Write a ~200-word style-bible paragraph** — exact medium, line quality, palette (name the colors precisely), grain/texture, panel framing, lighting logic. Paste it verbatim as a prefix on every single prompt. Never re-paraphrase it fresh each time — repeating identical style-language, not clever variation, is what keeps 24 images looking like one book.
2. **Generate a character sheet first**, before any chapter art: a multi-pose grid showing Wendell as a head-only (age 7), mid-transformation, as a boy (7–12), as a young drifter (12+); the father; the mother; the church interior; later, Munro, Crane, and Ruth once you reach their chapters. Get this locked and approved before touching Chapter 1 — it's the visual anchor for everything after.
3. **Condition every new image on the character sheet plus the most recently accepted image**, using ChatGPT's reference-image attachment — text prompts alone drift over 20+ generations; image-conditioning is what actually holds a face and style steady.
4. **Stay in one long conversation (or one per 4–5 chapter batch)** and use in-context editing turns ("make the hands larger, darken the background") rather than starting fresh threads — GPT Image 2's real strength is multi-turn editing, not one-shot generation.
5. **Save every accepted image with its exact final prompt text**, filed per chapter, so a cover or marketing image months later can match the established style without reconstructing the method from memory.

## Budget expectation

5–10 generations per finished illustration once the style bible and character sheet are locked (expect 10–15 for the first few, while still dialing those in). For 24 chapters: **roughly 150–250 total generations**, done in batches of 4–5 chapters per sitting so fatigue and drift don't creep in. Time-budget: 1–2 hours per finished illustration including selection and touch-up.

---

## Per-chapter concept notes

One illustration per chapter. These are composition/mood notes to build actual prompts from later, not finished prompts — write the real prompt at generation time using the style-bible prefix plus the relevant note below.

### Book One — The House
1. **The body unfolding in church light** — night interior, stained-glass color pools on stone floor, a stalk-like form rising and unfurling from the neck-stump; treat as botanical miracle, not surgery — no anatomical literalism.
2. **First run through the back pasture** — full-body motion, linocut speed-lines, fence line receding, a dog or crows scattering; the book's one unclouded image of joy.
3. **Leaving at twelve, dirt road at dawn** — small figure, long shadow behind him, sack over one shoulder, road vanishing to a flat horizon.

### Book Two — Apprenticeship in Being Seen
4. **The barn, lantern-lit** — Silas Boyd's gun barrel and lantern in the frame, Wendell's face half-lit in a hay-loft doorway, tension held in negative space.
5. **Munro at the water tower** — two silhouettes at dusk by a rail line, one old and stooped, one young, a thin fire between them.
6. **The empty ring** — town square or church steps, Wendell at the center of a loose circle of townspeople all keeping their distance; the empty space itself is the image's subject.
7. **Dry season, night** — a line of distant lantern/torch light across cracked, drought-split ground, Wendell running, small against the dark.
8. **Vesta Coombs' kitchen** — warm interior lamp light (the accent color used generously here, a deliberate contrast to Ch. 7's darkness), a bandaged hand on a table, quiet domestic stillness.
9. **The medicine show at dusk** — a lit revival tent and banner, crowd silhouettes pressed toward it, Wendell alone at the crowd's edge, watching rather than joining.

### Book Three — The Exhibition
10. **Terms** — Crane and Wendell face to face inside the tent, Crane backlit and taller in the composition, a handshake or a paper between them.
11. **The living testament** — Wendell on a stage platform under lantern light, a sea of upturned crowd-faces below, a banner behind him.
12. **What it buys** — coins and a folded bill on a table beside a hand-lettered testimony card; something in the image quietly slightly wrong.
13. **The ask** — Crane leaning close in shadow, a hidden prop or second figure just visible at the frame's edge.
14. **Walking off the stage** — Wendell mid-stride out of the tent, backlit by the stage lights behind him, the crowd's confusion rendered as a blur of turned heads.

### Book Four — The Mirror
15. **Ruth Calloway** — a porch or roadside, her prosthetic or crutch shown plainly and without spectacle, a direct and unimpressed gaze at Wendell.
16. **Working together** — the two of them mid-task, practical and equal, no romantic framing, ordinary daylight.
17. **The first real fight** — the two of them in the same frame but apart, a doorway or threshold literally between them.
18. **Staying** — a small rented room, Wendell at a window looking in rather than out at a road for the first time in the book.
19. **The knock** — a door, two shadows cast long across a floor, tension held in stillness.

### Book Five — Reckoning
20. **What followed him** — distant figures arriving at a town's edge, Wendell and Ruth small in the foreground, already turning to look.
21. **Mercy or the other thing** — tight composition on Wendell's hand near an object of potential violence, his face the real subject.
22. **The cost paid** — quiet aftermath, a tended wound, empty space where someone or something was.
23. **The house again** — the same porch/threshold from Chapter 1's imagery, Wendell now grown, the father small in a chair facing away — a deliberate visual rhyme with the opening chapters.
24. **Rolling** — the same road as Chapter 3's opening, but the shadow now falls behind him rather than ahead — closing bookend, dawn light, Ruth beside him if the ending keeps her there.
