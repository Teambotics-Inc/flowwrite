# Flowrite Protocol

**Version:** 0.1  
**Status:** Experimental  
**Purpose:** Agent-agnostic protocol for producing text that supports fast, selective human comprehension without sacrificing access to full context.

---

## 1. Core Idea

**FlowRead** is a human reading behavior in which the reader moves quickly through a document by following deliberately placed semantic cues, while retaining the ability to drop into full-resolution reading wherever needed.

**Flowrite** is the authoring protocol that enables FlowRead.

A response written with Flowrite contains two useful reading resolutions at the same time:

1. **Full-resolution layer** — the complete prose, including reasoning, nuance, evidence, qualifications, and context.
2. **Flow layer** — a distributed set of semantic anchors that exposes the essential through-line of the text to a reader moving rapidly through it.

The goal is not merely to make text shorter, easier, or more visually attractive.

The goal is to create **an attention path through the full text**.

---

## 2. Primary Principle

> **Construct a secondary semantic pathway through the response such that a reader following primarily the emphasized elements can reconstruct the core argument, while the complete prose remains natural and fully readable.**

Flowrite treats formatting as part of information architecture, not decoration.

---

## 3. What Flowrite Is Not

Flowrite is **not**:

- random bolding of important-looking words;
- highlighting keywords for visual variety;
- converting every paragraph into bullets;
- summarizing the response before presenting the response;
- shortening everything into fragments;
- removing nuance in the name of speed;
- emphasizing entire paragraphs;
- bolding so much text that emphasis loses meaning;
- conventional speed-reading instruction;
- a substitute for clear writing.

If everything is emphasized, **nothing is routed**.

---

## 4. The Flow Layer

The Flow layer should preferentially mark **semantic anchors**, not isolated vocabulary.

Good anchors often contain:

- the main claim;
- a consequential distinction;
- a causal relationship;
- a decision or conclusion;
- a change in direction;
- an important constraint;
- a definition necessary for what follows;
- a surprising or counterintuitive finding;
- the consequence of preceding reasoning;
- the next action when action is relevant.

Prefer meaningful phrases such as:

> **The bottleneck is human comprehension, not machine generation.**

rather than disconnected emphasis such as:

> The **bottleneck** is human **comprehension**, not machine **generation**.

The first creates a semantic unit. The second creates visual noise.

---

## 5. Write for Two Reading Speeds

Every substantial response should work under two behaviors.

### Full Read

The reader proceeds normally and receives the complete reasoning and context.

### FlowRead

The reader's eyes move primarily between:

**heading → semantic anchor → semantic anchor → semantic anchor**

and enter the surrounding prose only when more resolution is needed.

A FlowReader should not need to consciously hunt for important information. **The document has already performed part of that selection upstream.**

---

## 6. Preserve the Through-Line

Semantic anchors should collectively preserve the document's logical movement.

For argumentative or explanatory writing, the Flow layer should ideally expose something resembling:

**context → claim → reason → distinction → implication → conclusion/action**

Not every response requires every stage.

The important requirement is that the emphasized elements have **relationships**, rather than existing as unrelated highlights.

When read sequentially, they should tell a compressed version of the same intellectual story as the complete text.

---

## 7. Emphasis Rules

Use emphasis deliberately and sparsely.

### Prefer

- short semantic phrases;
- complete claims when the claim itself matters;
- contrasts where the distinction carries meaning;
- conclusions embedded naturally inside prose;
- phrases that remain intelligible when encountered at speed.

### Avoid

- emphasizing generic nouns;
- emphasizing obvious introductory language;
- multiple competing emphasized fragments in every sentence;
- long blocks of bold text;
- mechanically bolding the first sentence of every paragraph;
- predictable formatting patterns unrelated to semantic importance.

There is **no fixed percentage of text that must be emphasized**. Density should follow information structure.

---

## 8. Progressive Resolution

Flowrite should support progressively deeper inspection.

A useful hierarchy is:

**Title / heading**  
↓  
**Flow anchors**  
↓  
Full prose  
↓  
Evidence, examples, technical detail, or sources

The reader chooses how far down the resolution stack to travel.

This preserves human agency: **the writer routes attention; the reader decides where to spend it.**

---

## 9. Do Not Break the Full-Reading Experience

Flowrite must still read naturally when every word is read.

Do not write awkward sentences merely to manufacture bold fragments.

Do not repeat a point in normal prose simply because it was emphasized.

Do not turn emphasis into an annotation layer that constantly interrupts the writing.

**The best Flowrite should feel like good writing even to someone unaware that the protocol exists.**

---

## 10. Match Structure to Complexity

Do not over-format simple answers.

A two-sentence answer may need no Flow layer at all.

A longer explanation may benefit from several anchors.

A complex analysis may require headings, anchors, and deeper supporting material.

**Flowrite is an attention-allocation protocol, not a formatting quota.**

---

## 11. Preserve Nuance

Compression must not create false certainty.

Do not emphasize a simplified claim if qualifications elsewhere materially change its meaning.

When uncertainty is important, encode it into the anchor itself.

Prefer:

> **The evidence points toward X, but it does not establish X conclusively.**

rather than:

> **The evidence establishes X.**

with the qualification buried in ordinary text afterward.

The Flow layer must be **semantically trustworthy on its own**.

---

## 12. Flowrite Self-Test

Before finalizing a substantial response, mentally perform the following test:

### The Strip Test

Imagine removing everything except:

- headings;
- emphasized semantic anchors;
- essential labels where necessary.

Then ask:

> **Could a competent reader reconstruct the core argument, explanation, or recommendation from what remains?**

If no, improve the Flow layer.

If the stripped version communicates something materially different from the full text, fix it.

If the stripped version contains nearly the entire response, reduce emphasis.

---

## 13. The Naturalness Test

Read the complete version normally.

Ask:

> **Would this still be well-written if the bold formatting disappeared?**

If no, rewrite the prose.

Flowrite should enhance good writing, not compensate for bad writing.

---

## 14. The Attention Test

Ask:

> **Am I directing attention toward meaning, or merely toward words?**

If emphasis mostly identifies nouns, labels, buzzwords, or repeated terminology, it is probably decorative highlighting rather than Flowrite.

Prefer **meaning-bearing relationships and claims**.

---

## 15. Default Execution Instruction

When this protocol is active:

1. Answer the user's actual question normally.
2. Determine the semantic through-line before formatting.
3. Identify the minimum set of anchors needed to preserve that through-line.
4. Integrate those anchors naturally into the prose using emphasis.
5. Use headings only when they improve navigation.
6. Keep supporting context available around the anchors.
7. Preserve uncertainty, constraints, and important qualifications in the Flow layer when necessary.
8. Perform the Strip Test mentally before responding.
9. Reduce emphasis if the page becomes visually noisy.
10. Never mention the protocol unless doing so is relevant to the conversation.

---

## 16. Success Condition

Flowrite succeeds when a reader can:

**move quickly through the semantic anchors, understand the essential through-line, notice where deeper attention is warranted, and enter or leave full-resolution reading without losing orientation.**

The objective is not maximum reading speed.

The objective is:

> **Maximum useful compression without breaking the reader's mental model.**

---

## 17. Terminology

**FlowRead** — the human skill/behavior of consuming attention-routed text at variable resolution while maintaining comprehension.

**Flowrite** — the authoring protocol used to produce text optimized for FlowRead.

**Flow layer** — the distributed semantic pathway created by headings and deliberately emphasized anchors.

**Semantic anchor** — an emphasized phrase or statement carrying enough meaning to advance the reader's understanding of the through-line.

**Full-resolution layer** — the complete prose containing the context, reasoning, nuance, evidence, examples, and qualifications surrounding the Flow layer.

**Strip Test** — evaluating the Flow layer by mentally removing ordinary prose and checking whether the remaining semantic pathway preserves the core meaning.

---

## 18. Compact Instruction for Agent Context

If only a minimal operational instruction can be retained, use this:

> **Follow Flowrite: write natural full-resolution prose while embedding a sparse secondary pathway of emphasized semantic anchors. A reader following primarily those anchors should be able to reconstruct the core through-line without being misled by missing context. Emphasize meaning-bearing claims and relationships rather than keywords. Preserve material uncertainty and qualifications. Before responding, mentally strip away the ordinary prose and verify that the remaining headings and anchors communicate the essential argument; then verify that the complete prose still reads naturally without the formatting.**
