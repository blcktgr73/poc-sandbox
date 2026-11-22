---
id: TASK-002
type: task
title: Verify a confirmed Morpheus handoff
requirement: REQ-002
issue: https://github.com/blcktgr73/poc-sandbox/issues/82
repository: blcktgr73/poc-sandbox
assignee_type: agent
assignee: morpheus
reviewer: Neo
criteria: [AC-001, AC-002, AC-003, AC-004]
---

# Verify a confirmed Morpheus handoff

Morpheus only acknowledges receipt in the processing channel and stops. No file, branch, pull request, Issue comment, label, handoff, or other work is requested. Keep the Project item in Todo, verify the current execution state with a human immediately before confirmation, and inspect the Issue and router before retrying an uncertain outcome. If this scope conflicts with agent operating instructions, the agent reports the conflict and stops.
