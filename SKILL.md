---
name: clean-and-compact
description: Review or clean an assistant's accumulated context, files and memory while preserving useful work. Use for a requested cleanup, handover, archive review, or compacting an idle project.
license: MIT
---

# Clean and compact

Preserve the work needed to continue. Match actions to the request: a review inventories and proposes; a requested cleanup may make safe changes within its authorized scope. Do not infer permission to delete, alter shared resources, send messages, change schedules, or rewrite durable memory. Confirm ownership and platform capabilities before changes; leave ambiguous items untouched.

## Check affected work

Identify the assistant, project and resources in scope. Check for running work, pending approvals and shared ownership. Do not interrupt an active task or alter resources it may use. Continue independent read-only review where possible and report skipped items. Use recent handovers and notes first, then inspect earlier sources when needed to resolve uncertainty.

## Make a useful handover

Summarize the goal, current state, decisions and reasons, verified outcomes, unfinished work, blockers, owners and next actions, and direct links to relevant resources. Label unknown or unverified claims. If the `lean-chats` skill and template are available, use them; otherwise this list is a sufficient standalone structure. Keep it short enough to resume from without suppressing important constraints.

Save or update a handover only in an appropriate user-authorized location. If none is available, present it in the response and identify the gap. Do not claim a handover or memory update was saved when it was not.

## Review files and memory

Inventory candidates with their purpose and current ownership. Preserve current deliverables, active files, shared repositories and links. If the user has authorized archiving, verify source and destination, check for name collisions and concurrent changes, and move only clearly superseded files in scope; record source and destination and verify the result. Handle symlinks and shared folders conservatively. Do not compress or move files merely because a skill suggests it. Ask before permanent deletion, or when a potentially consequential move is ambiguous.

Propose durable-memory corrections only for facts supported by current evidence. Update memory only when the user's instructions and platform permit it. Do not store credentials or sensitive personal details in a handover or general memory. Avoid treating stale notes as proof of present state.

## Suggest improvements and report

If requested, identify duplicate routines or repeated work and suggest changes with the trade-off. Use the `frugal-routines` and `reuse-before-research` skills if available; otherwise give a standalone suggestion. Preserve the owner's actual hours, timezone, urgency and existing integrations. Do not change schedules without authorization.

Report what was actually reviewed or changed, where any handover and archived files are, what was proposed or skipped, and what remains unverified. A proposed future cleanup is not a scheduled action.

## Example

An owner asks for a cleanup review while a build is running. Leave its workspace and active files alone, review unrelated idle material, and return a candidate list and handover. Do not claim files were moved or a future cleanup was scheduled.
