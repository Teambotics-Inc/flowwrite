# FlowWrite

**An agent-agnostic writing protocol for attention-aware reading.**

FlowWrite structures natural prose so it can be understood at two resolutions: the complete text and a sparse path of meaning-bearing **semantic anchors**. Its companion concept, **FlowRead**, describes the reader's ability to move between those resolutions without losing the argument.

**The writer routes attention. The reader decides where to spend it.**

## Why FlowWrite?

Digital writing is easy to generate and increasingly difficult to navigate. A summary can remove necessary context; indiscriminate emphasis adds noise. FlowWrite offers another approach: **retain the complete explanation while making its intellectual through-line easy to follow**.

FlowWrite is a writing protocol, not a speed-reading technique, markup standard, or software product. It can be applied by human authors, AI assistants, editors, and documentation systems.

## How it works

A FlowWritten document has two complementary layers:

| Layer | Purpose |
| --- | --- |
| **Full-resolution layer** | The complete prose, including reasoning, evidence, qualifications, examples, and nuance. |
| **Flow layer** | A limited set of emphasized statements and headings that conveys the essential through-line when read in sequence. |

Semantic anchors should communicate **claims and relationships**, not just highlighted keywords. They should remain accurate when read apart from surrounding prose.

For example:

**FlowWrite:** **The bottleneck is human comprehension, not machine generation.** More text is useful only when readers can locate and evaluate what matters.

**Not FlowWrite:** The **bottleneck** is human **comprehension**, not machine **generation**.

The first emphasis is a coherent proposition. The second requires the reader to reconstruct one.

## Three checks

1. **Strip Test** — Read only the headings and emphasized anchors. Does the essential argument still hold, including important qualifications?
2. **Naturalness Test** — Remove the emphasis. Does the complete text still read well?
3. **Attention Test** — Does each anchor direct attention to meaning rather than decorate the page?

There is no required amount of bold text. **Emphasis density follows the argument, not a quota.**

## Use FlowWrite with an AI assistant

Include this short instruction in your agent's writing guidance:

> Follow FlowWrite: write natural full-resolution prose while embedding a sparse secondary pathway of emphasized semantic anchors. A reader following primarily those anchors should be able to reconstruct the core through-line without being misled by missing context. Emphasize meaning-bearing claims and relationships rather than keywords. Preserve material uncertainty and qualifications. Before responding, mentally strip away the ordinary prose and verify that the remaining headings and anchors communicate the essential argument; then verify that the complete prose still reads naturally without the formatting.

See the protocol's [complete operational guidance](FLOWWRITE_PROTOCOL.md#18-compact-instruction-for-agent-context) for the original wording and the full criteria.

## Specification

Read **[FlowWrite Protocol v0.1](FLOWWRITE_PROTOCOL.md)** for definitions, principles, emphasis rules, tests, and the complete agent instruction.

The initial specification is preserved unchanged as a source artifact. Changes to the protocol should be proposed separately from editorial improvements to this README.

## Project status

**v0.1 · Experimental.** FlowWrite is a documented writing approach, not a tested claim of universal reading-speed or comprehension improvement. Evaluation methods and examples may evolve with use.

### Contributing

Issues and pull requests are welcome for corrections, examples, accessibility considerations, and proposals to improve the protocol. Please distinguish proposed changes from the original v0.1 specification.

### Licensing

**No license has been selected.** A public GitHub repository does not itself grant permission to reuse, modify, or redistribute its contents. Licensing can be added once the project owner selects appropriate terms.

---

Maintained by **[TeamBotics Inc.](https://github.com/Teambotics-Inc)**.
