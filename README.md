# Prepare Advisor Materials

A local Codex Skill for preparing fixed-version code evidence and targeted same-version supplements for a task-bound advisor. This is the latest source snapshot published on 2026-10-21.

Read [SKILL.md](SKILL.md). After cloning, make this directory available as the `prepare-advisor-materials` Skill in your Codex skills directory. Compare any existing installation before replacing it. Invoke `$prepare-advisor-materials`, or ask to prepare the current task's code for its bound advisor.

## Companion and dependencies

The optional cloud advisor rules are published separately as [chat-project-advisor](https://github.com/ShengHuang21/chat-project-advisor). This local Skill uses existing Git/file tools. It prepares materials; it does not install communication tools or grant permission to send them.

The current instructions refer to an existing `manage-personal-task-workspace` advisor loop for authorized recipient binding, serial send/read matching and integration. That separate component is not bundled in this repository or made public by this release. If it is unavailable, this Skill can still prepare a local packet; automatic end-to-end exchange is not provided by this repository alone.

No credentials, company task material, local task receipts or private repository history are included. Publishing this source does not change local installation links or the visibility of any cloud plugin.
