# Versioned Memory and Continuation

Chapter memory is a versioned summary, not a replacement for the manuscript. Store the manuscript version, upstream dependencies, synopsis, viewpoint, time/place, character changes, and setup/payoff evidence. Distinguish facts, beliefs, and speculation. After prose or dependencies change, mark affected memories and reviews pending recheck rather than copying old summaries. Assess adjacent transitions and distant clues according to actual impact; broaden the check when evidence requires it.

Update a short continuation entry before dispatch, after delivery and adjudication, before and after authoritative saves, and at chapter/review-batch boundaries. Do not wait for context exhaustion or promise switching at a fixed percentage when remaining capacity is not visible.

Persist goals, new author decisions, planning links, stable task IDs, dependencies and input versions, worker IDs when available, statuses, artifact paths, unreviewed findings, before/after save versions, readback/synchronization state, and the next concrete action. Distinguish running, delivered awaiting review, revising, accepted, save result unverified, saved awaiting synchronization, and closed.

Subagents save intermediate artifacts, not just chat messages. Before a lead handoff, close out the current batch and persist unfinished work. Do not assume a new chat controls old agent IDs. Recovery begins by querying accessible runtime status, reading artifacts, and checking versions, then resumes the smallest unfinished unit. Late results never automatically overwrite a newer draft.

Allow one authoritative writer per task. If a save outcome is unknown, inspect the actual manuscript and history first. If saved, finish readback/synchronization; if not saved and the baseline still matches, proceed. Otherwise leave it unverified rather than blindly retrying. A checkpoint is not an atomic lock; concurrent processes require real tool locks or stopped parallel writes.

Record the previous writer, verifiable stopped/released status, successor, and handoff time. If another authoritative writer might still be running and cannot be ruled out, keep final writes pending. Naming a successor does not create mutual exclusion; read-only checks and separate candidate preparation may continue.

Do not automatically create a new chat. If the user chooses one, provide the project root, continuation entry, and next action without requiring a full retelling. Do not substitute rereading the whole novel or repeating accepted work for recovery.
