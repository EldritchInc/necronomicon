# Small Forces (Book One of The Drift Trilogy)

**Partial: 1 chapter written of 18 planned.** Written by [Azathoth](https://github.com/EldritchInc/azathoth)'s novel example.

## Why it stopped

```text
ToolExecutionError: Tool implementation c1000000-0000-4000-8000-000000000012 exited with status 1: Iteration 2: child workflow e1000000-0000-4000-8000-000000000040 invocation 6f5d4b2c-c2a3-4a30-a344-bdd0090a17a9 failed: Production workflow execution failed.
```

Underlying failures:

```text
write-chapter 0042: ModelExecutionError: OpenRouter request for model 'anthropic/claude-opus-5.5' failed.
write-chapter 0042: ModelExecutionError: OpenRouter request for model 'anthropic/claude-opus-5.5' failed.
```

## Premise

In 2219 the Belt runs on water, credit and insurance. Piq Adebayo-Lund is a field assessor for the Assessment Office of the Ceres Mutual Assurance Compact. The Compact underwrites nearly every Belt habitat, and its actuaries are, in all but name, the Belt's intelligence service. Piq travels under a cover that is technically true: she holds a real Ceres Registry commission as a notary and marriage celebrant, and her notarial seal doubles as a Compact optical authentication key. She boards the Mars–Ceres cycler Patience with one job. The ship will fly past Vesta in 140 days, and she must confirm whether the Martian-aligned Vesta Works has built a mass driver to throw kinetic weapons at Ceres. Aboard she meets Teodora 'Teo' Anselm, the ship's trajectory and mass officer. Teo is careful, wry and quietly grieving, and she is the only person aboard who can read orbits the way Piq reads people. Piq mistakes a test flash for an attack and sends a report she cannot recall, at the speed of light. She and Teo then discover three things. The driver is not a weapon. The thing it is fighting was set loose by Ceres itself. And the 'confirmation' Piq sent has launched a silent interceptor that will destroy the only machine that can save her home. Stopping it means spending the water that shields them from the sun, aboard a small taxi with no way back, with the woman Piq has come to love beside her.

## Chapters

1. [Before You Begin](chapters/01.md)

The whole book is in [book.md](book.md).

## The run

| | |
| --- | --- |
| Started | 2026-10-27 17:53 UTC |
| Duration | 13 min |
| Model calls | 9 |
| Tokens | 127,725 in, 69,218 out |
| Recorded cost | $1.90 |
| Models | `anthropic/claude-opus-5.5` |
| Novel run | `7da46f05-86db-4ac3-8d3a-b55dbb0e2781` |

Failed attempts record no usage, so the provider's bill can be a little higher.

| Step | Calls | Cost | Models |
| --- | ---: | ---: | --- |
| revise-chapter: Apply editorial requests | 2 | $0.61 | `anthropic/claude-opus-5.5` |
| revise-chapter: Verify editorial requests | 2 | $0.11 | `anthropic/claude-opus-5.5` |
| write-chapter: Draft chapter | 1 | $0.31 | `anthropic/claude-opus-5.5` |
| write-chapter: Review chapter | 1 | $0.15 | `anthropic/claude-opus-5.5` |
| write-chapter: Update notes | 1 | $0.12 | `anthropic/claude-opus-5.5` |
| write-novel: Plan chapters | 1 | $0.21 | `anthropic/claude-opus-5.5` |
| write-novel: Plan story | 1 | $0.39 | `anthropic/claude-opus-5.5` |

## The idea

```text
Book one of a planned trilogy: a speculative hard science fiction novel that is equally a sapphic romance and a suspense thriller.

Protagonist: Piq, a woman who works as a spy in space. Decide who she spies for, her cover, her mission and the setting.

Hard science fiction: keep the physics consistent and plausible. No faster-than-light travel or communication. Light-speed delay, orbital mechanics, life support, radiation and the cost of moving mass should shape both the plot and the spycraft.

Romance: a slow-burn romance between Piq and one other woman, central to the plot rather than a side thread. It deepens through the story's events, and by the last chapter they choose each other, even though their future stays uncertain. The love interest is not an enemy agent and never betrays Piq.

Twists: at least three major twists, each of which changes how the reader understands what came before. No twist may be a betrayal: no ally secretly working for the enemy, no character lying about who they are. Build every twist from facts the reader was fairly shown earlier, such as a misread signal, a hidden physical constraint, a wrong assumption about time delay, a mission whose real purpose was different, or a consequence nobody predicted. Plant the clues for each twist at least two chapters before it lands.

Comedy: regular, genuinely funny situational comedy that grows out of the setting and the characters, such as cover identities colliding, microgravity mishaps, bureaucratic protocol, or a plan that works for the wrong reason. Humor never undercuts the suspense at the tensest moments.

Ending: by the final chapter, resolve the main arc, the central mystery, the romance and every subplot, with no dangling threads. Separately, choose exactly three deliberate sequel hooks for books two and three. Seed them through foreshadowing during the story and leave them open at the end. Name them in the plan's arc under the label "Deliberate trilogy hooks, left open on purpose", so that editors keep them and do not treat them as unresolved threads.

Style: write the plan's tone so it carries these requirements into every chapter: close third person on Piq, vivid but economical prose, chapters of about 4,000 to 5,000 words, and every chapter ending with forward momentum.
```

Full identity (revisions, run and invocation IDs) is in [provenance.json](provenance.json); the plan is in [story.json](story.json).
