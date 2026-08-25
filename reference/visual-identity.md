# Franklin — Core Visual Identity

This document is the canonical source of truth for Franklin's visual language. Use it when making or reviewing any decision about video art direction, Fusion compositions, motion graphics, stock footage, archival material, charts, documents, thumbnails, mascot usage, typography, transitions, sound design, or recurring visual systems.

## 1. One-sentence art direction

> **Franklin looks like an old financial archive being calmly dismantled and reconstructed by a modern analyst.**

The channel should feel neither purely historical nor purely modern. Its identity comes from combining:

- 18th/19th-century financial print and engraving;
- archival documents, newspapers, certificates, bonds, maps, photographs, and footage;
- modern institutional-finance imagery and data;
- restrained analytical motion graphics;
- cinematic 2.5D Fusion compositing;
- carefully selected stock footage;
- the engraved Franklin mascot;
- occasional understated gaming humour.

The result should feel authored, intelligent, tactile, calm, and slightly strange.

## 2. Core principle for every visual

Every visual must do at least one of four jobs:

1. **Establish reality** — show the place, person, institution, object, or historical moment being discussed.
2. **Provide evidence** — show the chart, document, quotation, number, filing, source, or archival record supporting the claim.
3. **Explain a mechanism** — make flows, incentives, relationships, chronology, balance-sheet effects, or causal links legible.
4. **Add personality** — use Franklin, a restrained visual joke, a gaming reference, or an editorial composition to give the channel a distinctive human voice.

If a shot does none of these, cut it.

## 3. Overall visual world

Franklin should sit between four aesthetics:

### Historical financial print

Use:

- engraved portraits;
- old newspapers;
- bond and share certificates;
- ledgers;
- handwritten letters;
- currency and banknote details;
- historical maps;
- legal and government documents;
- archival photographs and newsreels.

### Modern institutional finance

Use:

- clean charts;
- balance-sheet diagrams;
- simplified settlement and market-plumbing diagrams;
- official reports and filings;
- modern financial infrastructure;
- restrained data labels and numerical callouts.

### Cinematic compositing

Use Fusion to combine stills, footage, documents, Franklin, foreground elements, atmosphere, and camera movement into layered editorial scenes.

### Internet/gaming personality

Gaming is not the channel's subject. It is part of the creator's sensibility. References should appear occasionally as analogies, punchlines, props, visual callbacks, or miniature economic examples.

A gaming reference should be understandable even if the viewer has never played the game.

## 4. Colour system

The default world is mostly monochromatic and warm.

### Core palette

- **Paper / ivory:** `#E7E0D2`
- **Warm white:** `#F4F0E8`
- **Ink black:** `#191919`
- **Charcoal:** `#2B2B2B`
- **Old newspaper grey:** `#8C8981`

### Signature accent

- **Muted banknote green:** `#526B5A`

This is the default Franklin accent. It should feel like old currency ink, not bright finance-app green.

Use it for:

- primary chart series;
- selected keywords;
- important lines;
- subtle UI states;
- section accents;
- important document marks;
- occasional props or visual anchors.

### Secondary accent

- **Muted gold:** `#A88D57`

Use sparingly for:

- particularly important numbers;
- dates;
- historical milestones;
- rare secondary chart emphasis;
- subtle ornamental details.

### Other colours

Do not introduce a large rainbow palette simply because a chart has several categories.

Use neutral differentiation first:

- charcoal;
- grey;
- lighter/darker green;
- line style;
- direct labels;
- opacity;
- pattern.

Use muted semantic red only when a genuine negative/danger state requires it. Avoid bright red/green trading-screen language.

## 5. Texture

Digital perfection makes Franklin look pasted onto the footage. Texture should unify the world.

Use subtle:

- paper fibres;
- film grain;
- engraving dots;
- newspaper halftone;
- photocopy imperfection;
- slight ink bleed;
- deckled/torn paper edges where contextually useful.

Texture should usually be **felt rather than noticed**.

Typical overlay strength: approximately **3–8% opacity**, depending on the shot.

Create or maintain a reusable master treatment such as:

`FRANKLIN_MASTER_TEXTURE`

Potential ingredients:

- subtle grain;
- restrained contrast curve;
- mild warm tint;
- optional soft vignette;
- optional paper texture.

Modern stock footage does not always require paper treatment. Contrast between archival and contemporary imagery is useful.

## 6. Franklin mascot

Franklin is an editorial host, not an animated cartoon presenter.

The mascot should remain recognizably based on the engraved Benjamin Franklin portrait associated with the US $100 bill while functioning as a reusable illustrated character.

### Default behaviour

Franklin is usually:

- composed;
- deadpan;
- static or nearly static;
- introduced with slow parallax;
- moved with restrained position/scale changes;
- given a small prop or environmental interaction rather than broad cartoon acting.

### Comedy rule

**Franklin's default joke is that he does not react.**

A bank collapses: Franklin stares.

A chart goes vertical: Franklin stares.

A country defaults: Franklin stares.

An OSRS player loses an absurd amount of GP: Franklin stares.

Expression changes should therefore be rare and meaningful.

### Usage frequency

Franklin should not dominate every frame.

A useful default is to feature him prominently in roughly **20–35% of shots**, with substantial stretches where the evidence or story carries the frame alone.

### Asset library

Maintain reusable versions such as:

- portrait Franklin;
- full-body Franklin;
- seated Franklin;
- side-profile Franklin;
- pointing Franklin;
- small/tiny Franklin;
- silhouette Franklin.

Useful recurring props:

- newspaper;
- bond certificate;
- ledger;
- magnifying glass;
- briefcase;
- coin;
- chart;
- old telephone;
- fountain pen;
- umbrella;
- occasional gaming prop or armour for jokes.

Do not traditionally animate full limbs unless a specific visual genuinely benefits from it. Composite posing is usually enough.

## 7. Primary composition style: 2.5D editorial composites

Franklin's strongest recurring visual technique should be layered 2.5D scenes built in Fusion.

Typical stack:

1. background;
2. environment;
3. midground objects;
4. Franklin or historical subject;
5. foreground objects;
6. atmospheric texture;
7. Camera3D.

Historical photographs should often be separated into planes:

- sky/background architecture;
- main building or subject;
- crowds/people;
- foreground street or objects.

Add modest Z separation and a slow camera movement.

Typical duration: **5–10 seconds**.

The goal is not to make a still photograph look like a fake 3D film set. The goal is to give static evidence depth and deliberate visual attention.

## 8. Editorial collage

Compositions may combine:

- one photograph;
- one newspaper headline;
- one document fragment;
- a chart or number;
- Franklin;
- handwriting or annotation.

But always maintain hierarchy.

Default rule:

- **one dominant object**;
- **two supporting objects**;
- everything else becomes quiet context.

Avoid random scrapbook clutter and fifteen overlapping clippings.

## 9. Motion language

Motion should be **slow, deliberate, tactile, and analytical**.

### Camera movement

Typical pushes or lateral moves:

- duration: **4–8 seconds**;
- scale change: approximately **100% → 108–115%**.

Use occasional longer 8–12 second compositions when new information develops inside the shot.

### Object motion

Prefer:

- position;
- scale;
- opacity;
- masks;
- crop reveals;
- Write On;
- restrained displacement;
- subtle easing;
- mild overshoot only when appropriate.

Avoid:

- constant elastic bounce;
- spinning;
- exaggerated motion blur;
- cartoon physics;
- hyperactive zooms;
- pointless whooshes.

The deep, calm narration should not be compensated for with frantic editing.

## 10. Paper as a physical object

Paper should feel tactile.

When introducing:

- a bond;
- legal document;
- letter;
- newspaper;
- quotation;
- balance sheet;
- official report;

consider having it physically enter frame as though placed onto a desk.

Typical treatment:

- 1–3° rotation;
- soft realistic shadow;
- slight paper texture;
- camera movement toward the relevant section.

This may become one of Franklin's signature visual actions.

## 11. Documents as environments

Do not repeatedly show a raw PDF and digitally zoom into a sentence.

A stronger workflow is:

1. show enough of the real page to preserve authenticity;
2. isolate the relevant paragraph, chart, heading, or number;
3. rebuild it inside Franklin's design system;
4. highlight the relevant phrase;
5. transition the phrase into the mechanism being explained.

Example:

`RESTRUCTURING CREDIT EVENT`

The phrase is pulled from an ISDA document.

The words separate, and the composition reveals:

Greek bond → CAC → Determinations Committee → auction.

Evidence becomes explanation.

## 12. Typography

Use two complementary typographic voices.

### Editorial serif

Preferred characteristics:

- classical;
- readable;
- restrained;
- suitable for historical and financial print.

Potential families:

- EB Garamond;
- Libre Baskerville;
- Cormorant Garamond;
- Crimson Pro.

Use for:

- chapter headings;
- dates;
- quotations;
- historical labels;
- dramatic single words;
- major title moments.

### Modern sans-serif

Potential families:

- Inter;
- IBM Plex Sans;
- Source Sans 3;
- restrained Helvetica-like grotesks.

Use for:

- chart labels;
- data;
- diagrams;
- explanatory captions;
- source labels;
- UI-like elements.

The pairing mirrors Franklin's identity:

**history + systems.**

Avoid making every text element Times New Roman. That becomes costume design rather than an editorial system.

## 13. Numerical design

Important numbers should feel deliberate.

Example:

`$2.89 BILLION`

with a small annotation:

`NET GREEK CDS SETTLEMENT • 2012`

Use tabular numerals when possible.

Good number animations:

- restrained counter;
- type-on;
- mask reveal;
- wipe;
- gradual build.

Avoid slot-machine rolling numbers unless the context specifically justifies it.

## 14. Charts

Charts must look native to Franklin rather than like exported Excel defaults.

Default style:

- warm white/paper background;
- faint gridlines;
- ink/charcoal labels;
- muted green primary series;
- grey/charcoal comparison series;
- muted gold only for exceptional secondary emphasis;
- direct labels instead of legends where practical;
- clear source/date/unit annotations.

### Animated chart rule

Build charts during narration rather than showing the full finished chart immediately.

Example sequence:

1. axis appears;
2. baseline or historical period appears;
3. line draws;
4. one event marker enters;
5. relevant region highlights;
6. camera or framing isolates the key insight.

The motion should explain the chart.

## 15. Mechanism diagrams

Fusion diagrams should remain visually simple.

Use:

- cards/rectangles;
- arrows;
- labelled flows;
- numbers;
- ledger entries;
- balance-sheet blocks;
- restrained icons.

Example:

`BANK A → CENTRAL BANK → BANK B`

Animate reserves, deposits, collateral, or payments between them.

Avoid shiny 3D coins flying through pipes.

The mechanism is the spectacle.

## 16. Stock footage

Stock footage has three main jobs.

### Reality

Use real footage for:

- banks;
- streets;
- factories;
- ports;
- homes;
- consumers;
- offices;
- ATMs;
- governments;
- protests;
- trading infrastructure.

### Atmosphere

Use selectively for:

- clocks;
- rain;
- printing presses;
- trains;
- machinery;
- cities;
- macro financial environments.

### Visual reset

After dense charts, documents, and diagrams, use a well-chosen 4–6 second real-world shot to let the narration breathe.

### What stock footage should not do

Do not literally illustrate every noun.

Bad pattern:

- narration says “banks” → smiling banker typing;
- narration says “interest rates” → laptop candlestick chart;
- narration says “fear” → worried businessman.

That is generic corporate YouTube.

Use stock cinematically and contextually, not as a literal visual thesaurus.

## 17. Stock colour treatment

For historical-adjacent sequences:

- reduce saturation;
- warm highlights slightly;
- use soft contrast;
- add restrained grain;
- add very mild bloom when useful.

For contemporary footage:

- retain more natural colour;
- control saturation;
- maintain rich but not crushed blacks;
- keep the image editorial rather than teal-and-orange cinematic.

## 18. Archival footage and evidence

Archival footage should be used heavily when available:

- old Wall Street footage;
- bank runs;
- historical news reports;
- congressional/parliamentary footage;
- trading floors;
- financial infrastructure;
- public interviews;
- printing presses;
- protests and queues;
- government announcements.

When useful, add a small source treatment:

`SOURCE • YEAR • LOCATION`

Archive material should feel like evidence, not merely decoration.

## 19. Newspaper headlines

Headlines can become a recurring signature.

Preferred sequence:

1. paper enters frame;
2. camera approaches;
3. surrounding copy darkens or falls away;
4. headline remains readable;
5. one phrase receives a restrained underline/highlight;
6. transition into archival footage or mechanism.

Avoid generic fullscreen headline screenshots when the same information can be staged editorially.

## 20. Transitions

Maintain a small reusable transition vocabulary.

Primary options:

1. **Hard editorial cut** — the default.
2. **Paper wipe** — a document passes across frame.
3. **Match cut** — one visual shape becomes another.
4. **Camera push-through** — push into a newspaper/photo/document and emerge inside a new environment.
5. **Ink/engraving reveal** — historical sequences only; use sparingly.

Do not build dozens of unrelated Fusion transitions.

### Signature transition: engraving → reality

A particularly strong Franklin transition is:

1. engraved/illustrated financial environment;
2. camera pushes toward a real object or location;
3. engraved linework dissolves;
4. scene becomes archival or modern footage.

This expresses the channel's identity directly: historical financial representation becoming real-world mechanism.

## 21. Chapter cards

Keep chapter markers short and restrained.

Example:

`03`

`THE AUCTION`

Possible visual:

- Franklin silhouette;
- warm paper;
- serif heading;
- 1.5–2 second duration.

Better still: integrate chapters into the environment.

Example: a folder opens and the title on the document inside is the chapter heading.

## 22. Gaming references and humour

Gaming references should feel like the creator's personality intruding briefly into a serious finance documentary.

Good uses:

- market liquidity via an MMO auction house;
- sunk costs via a long grind;
- default waterfall as a dungeon descent;
- RuneScape banking as an absurd storage-system joke;
- price discovery through the Grand Exchange;
- leverage explained as a strategy that works until one unexpected mechanic wipes the party.

### Frequency

Keep references sparse enough that each one feels intentional.

### Visual treatment

Sometimes translate the game into Franklin's own visual language rather than dropping in an untouched screenshot.

Example:

An engraved Grand Exchange labelled:

`GRAND EXCHANGE`

`EST. 2007`

with Franklin standing beside it.

The contrast is the joke.

### Comedy restraint

Avoid:

- meme sound spam;
- repeated reaction zooms;
- TikTok captions;
- jokes every thirty seconds;
- references that require knowledge of the game to understand the finance.

## 23. Music

The voice is the primary instrument.

Preferred musical states:

### Investigation

- minimal piano;
- ticking rhythm;
- restrained analogue texture.

### Explanation

- low ambient bed;
- understated documentary score.

### Escalation

- low strings;
- subtle percussion;
- controlled tension.

### Historical reflection

- warm piano;
- restrained chamber/orchestral texture.

Avoid permanently epic scoring.

Silence should be used deliberately after important lines or reveals.

## 24. Sound design

Use quiet tactile sounds:

- paper;
- pencil;
- fountain pen;
- typewriter;
- document stamp;
- camera shutter;
- coin;
- clock;
- folder;
- market bell;
- restrained UI ticks.

The viewer should feel motion graphics have weight without hearing an action trailer.

## 25. Narration pacing and shot rhythm

The deep, soothing voice should be supported rather than fought.

Default average shot length:

**3–7 seconds**

with occasional:

**8–12 second developing compositions.**

A long shot should continue evolving internally.

Example:

0s — bank exterior;
2s — Franklin enters;
4s — headline appears;
6s — key number appears;
8s — cut.

This maintains information density without frantic editing.

## 26. Evidence on screen

Non-obvious claims should often receive visual proof.

Example narration:

> S&P classified Greece as being in selective default.

Visual:

- real S&P document;
- relevant phrase highlighted;
- small source annotation:

`S&P • FEB 27 2012`

The research depth should be visible in the edit.

The viewer should repeatedly feel that the argument is built from evidence rather than simply narrated with confidence.

## 27. Screenshots

Raw screenshots should rarely remain raw screenshots for long.

Preferred sequence:

1. briefly establish the authentic source page;
2. isolate the relevant section;
3. reconstruct the useful information in Franklin's visual system;
4. keep source identity visible where necessary.

Sources may include:

- Federal Reserve;
- ECB;
- Bank of England;
- IMF;
- World Bank;
- ISDA;
- company filings;
- government documents;
- historical newspapers;
- academic papers.

Never transform a source in a way that changes its meaning or removes essential context.

## 28. Minute-to-minute visual rhythm

A useful recurring sequence is:

1. **Cinematic/atmospheric** — archive, stock, historical composite;
2. **Analytical** — diagram, chart, number;
3. **Evidence** — source, document, quote;
4. **Character** — Franklin or restrained joke;
5. **Reset** — simple real-world footage or clean composition.

Do not follow this mechanically, but use it to avoid long monotony in any one visual mode.

## 29. Reusable Franklin desk

Build a recurring overhead or shallow-3D financial desk environment.

Possible permanent elements:

- dark or warm neutral desk;
- ivory papers;
- fountain pen;
- ledger;
- newspaper;
- bond certificates;
- photographs;
- occasional coffee;
- Franklin portrait or mascot.

Each video places new evidence on the same conceptual workspace.

Examples:

### Greece CDS episode

- Greek bond;
- ISDA document;
- newspaper;
- auction result.

### Panic of 1907

- bank certificate;
- J.P. Morgan portrait;
- panic headline;
- Clearing House certificate.

The desk should become Franklin's mental workspace rather than a literal physical set that must appear constantly.

## 30. Fusion preset library

Build reusable templates/comps for:

- `FRANKLIN_MASTER_TEXTURE`
- `FRANKLIN_PAPER_CARD`
- `FRANKLIN_NEWSPAPER_HEADLINE`
- `FRANKLIN_DOCUMENT_HIGHLIGHT`
- `FRANKLIN_DATE_CARD`
- `FRANKLIN_BIG_NUMBER`
- `FRANKLIN_CHART_AXIS`
- `FRANKLIN_CHART_LINE`
- `FRANKLIN_2_5D_PHOTO`
- `FRANKLIN_QUOTE`
- `FRANKLIN_SOURCE_LABEL`
- `FRANKLIN_CHAPTER`
- `FRANKLIN_INK_REVEAL`
- `FRANKLIN_PAPER_TRANSITION`
- `FRANKLIN_MAP`
- `FRANKLIN_BASIC_FLOW_DIAGRAM`

The goal is to make later videos faster without making them visually repetitive.

## 31. Thumbnail identity

Thumbnails should derive from the same visual system but be simpler and more aggressive in hierarchy.

Default rules:

- one major subject;
- Franklin only when useful;
- 0–4 words of text;
- ivory/black/green base palette;
- high contrast;
- minimal clutter;
- one visual contradiction, mystery, or mechanism.

Examples:

- Franklin between `DEFAULT` and `NOT DEFAULT`;
- ripped Greek bond;
- one enormous number over a historical document;
- an old financial object connected to a modern consequence.

Do not turn thumbnails into miniature versions of the full video composition.

## 32. What Franklin must not become

### Not generic finance-bro YouTube

Avoid default visual dependence on:

- candlestick charts;
- green arrows;
- piles of dollars;
- luxury watches;
- Lamborghinis;
- skyscraper glamour;
- trader stereotypes.

### Not a generic Vox clone

Avoid:

- flat vector graphics as the entire visual language;
- bright primary colours;
- generic explanatory iconography dominating the video.

### Not a generic history channel

Avoid:

- sepia everything;
- endless Ken Burns moves;
- maps and orchestral music as the default solution to every historical section.

### Not generic AI video

Avoid:

- constant AI-generated historical imagery;
- uncanny reconstructions used as evidence;
- fake film artefacts everywhere;
- literal generated image for every sentence;
- visual inconsistency between scenes.

### Not a meme channel

Avoid:

- reaction-PNG spam;
- loud sound-effect punctuation;
- jump zooms;
- giant subtitles;
- humour replacing explanation.

## 33. Visual decision hierarchy

When choosing how to illustrate a line or section, prefer in roughly this order:

1. real evidence or real-world source;
2. archival footage/image;
3. purpose-built chart or mechanism diagram;
4. composed 2.5D scene using authentic assets;
5. stock footage with a clear contextual job;
6. Franklin reaction/personality beat;
7. generated imagery only when it is clearly illustrative and no more truthful visual source exists.

Do not use generated imagery as documentary evidence.

## 34. Final design test

Before approving a visual, ask:

- Does it feel like Franklin rather than generic finance content?
- Does it help establish reality, prove a claim, explain a mechanism, or add personality?
- Is the hierarchy immediately clear?
- Is the movement calm enough to fit the narration?
- Does the archival/modern mixture feel deliberate?
- Is the texture subtle rather than decorative?
- Is Franklin enhancing the scene rather than obscuring the evidence?
- Would the visual still work without a meme sound effect or hyperactive transition?
- If it contains a gaming reference, can a non-gamer still understand the finance?

If the answer is no, simplify or rebuild it.

## 35. Core identity summary

Franklin's defining visual contradiction is:

**old financial material + modern analytical reconstruction.**

The channel should look like a calm researcher has opened an archive, taken out the bonds, ledgers, photographs, regulations, charts, and strange historical artifacts that built the financial system, and then rebuilt their relationships in motion so the viewer can finally see how the machinery works.
