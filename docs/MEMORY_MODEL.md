# Memory model and handoff rules

## Canonical memory versus generated views

Canonical files are edited intentionally and own their facts. Generated views—search indexes, manifests, embeddings, dashboards, and summaries—may improve retrieval, but they must remain reproducible and replaceable.

If a generated view conflicts with a canonical source, the canonical source wins. If two canonical sources claim the same fact, create a conflict record instead of choosing silently.

## Information classes

A practical system may use four classes:

| Class | Example | Default handling |
|---|---|---|
| Public | Project README, sanitized templates | Shareable after review |
| Private | Preferences, personal plans, project details | Load only for relevant tasks |
| Sensitive | Identity, legal, health, finance, private communications | Explicit need and strict access control |
| Secret | Passwords, keys, tokens, recovery codes | Never store in the Life OS; use a secret manager |

Classification should influence retrieval before model selection, not after the content has already been sent.

## Memory promotion checklist

Before promoting an event or model output into durable memory, ask:

1. Will this matter again?
2. Is it a fact, preference, decision, question, or external claim?
3. What is the canonical home?
4. What supports it?
5. Is the evidence current enough?
6. Does an older statement conflict?
7. Should it remain `pending_verification`?
8. Is the sensitivity appropriate for this file and reader?

## Safe handoff protocol

Give a fresh assistant:

1. workspace rules (`AGENTS.md`);
2. root memory and project routers;
3. current state only if the task crosses projects or depends on today;
4. one task-specific project index;
5. exact canonical source sections;
6. a write-back destination and permission boundary.

Do not begin with full archives or conversation dumps.

## Conflict handling

When sources disagree:

- preserve both statements and their sources;
- label the current fact `pending_verification`;
- prefer newer direct evidence only when precedence rules allow it;
- add a bounded open loop with one verification action;
- update `last_verified` only after actual verification;
- archive superseded state while retaining provenance.

## Reconstruction test

Periodically use a model or account with no prior chat context. Ask it to:

- locate the canonical source for a selected topic;
- summarize the current state without copying history;
- identify one uncertain fact and its verification action;
- explain what it intentionally did not load;
- propose the correct write-back destination.

Score accuracy, unsupported inference count, sensitive over-retrieval, tokens used, and time to a useful next action.
