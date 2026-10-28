# The Water's Lying

**Partial: 6 chapters written of 18 planned.** Written by [Azathoth](https://github.com/EldritchInc/azathoth)'s novel example.

## Why it stopped

```text
ToolExecutionError: Tool implementation c1000000-0000-4000-8000-000000000012 exited with status 1: Iteration 7: child workflow e1000000-0000-4000-8000-000000000040 invocation 82ccb1ea-7aba-47b0-b5a5-58c87fa1e7ce failed: Production workflow execution failed.
```

Underlying failures:

```text
write-chapter 0042: ModelExecutionError: OpenRouter returned an invalid response for model 'anthropic/claude-opus-5.5'.
write-chapter 0042: ModelExecutionError: OpenRouter returned an invalid response for model 'anthropic/claude-opus-5.5'.
```

## Premise

In 2197, Piq Ansari-Holm, a Ceres-born field officer of the Ledger, the intelligence service of the Ceres Hydrological Compact, boards the Aldrin cycler Aubade under her genuine cover as a certified auditor for the Interplanetary Habitability Board. Ceres sells the water that shields every crewed ship in the inner system. Her mission is to assess, and if ordered to disable, the Umbrella, a prototype superconducting magnetic radiation shield that could make water shielding obsolete. She also has to learn how her predecessor aboard died. Teodor Vasz's last message read only 'The water's lying.' The Umbrella's lead physicist is Dr. Hana Szelig, brilliant, defensive and openly contemptuous of auditors. Piq's sign-off can end Hana's life's work. During the five-month fall to Mars the two women circle each other through audits, secrets and an amateur shipboard play. Piq then discovers that the ship cannot stop, cannot easily change course, and has quietly spent much of its shielding water as propellant. The shield she was sent to destroy may be the only thing that keeps 220 people alive through a solar storm. To save them, Piq has to choose between her service, the truth, and the woman she has fallen for, using information that is always minutes or hours out of date.

## Chapters

1. [Vacated](chapters/01.md)
2. [The Blank Line](chapters/02.md)
3. [Livestock Delay](chapters/03.md)
4. [Housekeeping](chapters/04.md)
5. [Casting Notes](chapters/05.md)
6. [Heater Test](chapters/06.md)

The whole book is in [book.md](book.md).

## The run

| | |
| --- | --- |
| Started | 2026-10-28 00:03 UTC |
| Duration | 45 min |
| Model calls | 34 |
| Tokens | 549,492 in, 252,671 out |
| Recorded cost | $7.25 |
| Models | `anthropic/claude-opus-5.5` |
| Novel run | `3b476066-e42f-4f21-8d6e-0ff220dca2db` |

Failed attempts record no usage, so the provider's bill can be a little higher.

| Step | Calls | Cost | Models |
| --- | ---: | ---: | --- |
| revise-chapter: Apply editorial requests | 7 | $2.27 | `anthropic/claude-opus-5.5` |
| revise-chapter: Verify editorial requests | 7 | $0.39 | `anthropic/claude-opus-5.5` |
| write-chapter: Draft chapter | 6 | $1.73 | `anthropic/claude-opus-5.5` |
| write-chapter: Review chapter | 6 | $0.79 | `anthropic/claude-opus-5.5` |
| write-chapter: Update notes | 6 | $1.37 | `anthropic/claude-opus-5.5` |
| write-novel: Plan chapters | 1 | $0.20 | `anthropic/claude-opus-5.5` |
| write-novel: Plan story | 1 | $0.50 | `anthropic/claude-opus-5.5` |

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
