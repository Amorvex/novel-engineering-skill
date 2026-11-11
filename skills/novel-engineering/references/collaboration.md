# Subagent Collaboration and Revision

Use subagents for substantial writing or batch review; handle simple tasks directly. Schedule within the environment's actual capacity without prescribing models or fixed team sizes. If subagents are unavailable, perform distinct review passes serially and state that they were not independent reviews.

| Role | Deliverable | Authority |
|---|---|---|
| Lead agent | Briefs, decisions, final drafts, acceptance and handoff records | Sole writer of the authoritative manuscript and shared fact sources |
| Writer | Candidate drafts, revisions, responses to feedback | Assigned artifact directory only |
| Continuity reviewer | Evidence about time, identity, abilities, space, knowledge, and causality | Does not edit authoritative prose |
| Literary reviewer | Suggestions about expression, pacing, voice, and scene effectiveness | Distinguishes constraints from preferences |
| Setup/payoff and records reviewer | Clue states, materials usage, memory update proposals | Does not turn plans into facts |
| Arc reading reviewer | Sequential reading effects with locations and evidence | Did not write the reviewed passage; activated by stage |

Give each task a stable ID, input manuscript/draft version, scope, goal, evidence, constraints, output path, and acceptance conditions. Assign one active writer per chapter. Parallel reading is allowed; concurrent overwrites of one draft are not. Subagents return conclusions, key evidence, and artifact paths rather than forcing the lead to absorb their full histories.

Normal sequence: writer submits a candidate; reviewers assess it; the lead consolidates and adjudicates feedback; the original writer revises; relevant reviewers recheck; the lead accepts and saves. The lead may fix clear minor errors directly. Establish a unified plan before cross-chapter structural changes and execute in dependency order. Normally finalize adjacent chapters sequentially; preparatory work on the next chapter must not treat an unsettled outcome as fact.

Each finding includes ID, location, version, evidence, impact, required correction/recommended improvement/acceptable as written, proposed action, and final disposition. Writers respond item by item. Allow justified retention; deliberate parallelism is not automatically an error. If two rounds fail to converge, narrow the disagreement and let the lead decide from evidence. Escalate only genuinely author-level choices, not routine implementation. Do not loop indefinitely or vote to change canon.

For batch scanner findings, delegate read-only review by type, then consolidate revisions by chapter. Inspect every occurrence, not just the first excerpt. Record corrected, retained with evidence, false positive, or awaiting author decision; the last remains open. A different count after changing rules does not mean the prose was repaired.
