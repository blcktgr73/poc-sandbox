---
id: REQ-002
type: requirement
title: Verify a confirmed Weaver agent handoff
status: in-progress
repository: blcktgr73/poc-sandbox
---

# Verify a confirmed Weaver agent handoff

## Acceptance criteria

- A human execution check and separate action confirmation precede a single agent-label action.
- Weaver records the action attempt and result; router delivery and agent acknowledgement are checked independently.
- The agent changes only the requested sandbox file and provides the verification result in a pull request.
- A reviewer checks the resulting pull request and evidence before merge.

## Tasks

- `TASK-002` Verify a confirmed Morpheus handoff — [Issue #82](https://github.com/blcktgr73/poc-sandbox/issues/82)
