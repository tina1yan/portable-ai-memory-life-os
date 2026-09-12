# Device inventory

Do not store credentials, tokens, cookies, recovery codes, remote-access secrets, public IP addresses, or precise locations.

| Device alias | Intended role | Workspace entry | Runtime/provider | Current state |
|---|---|---|---|---|
| MAIN-PC | Primary workspace | `pending_verification` | `pending_verification` | Active |
| BACKUP-LAPTOP | Lightweight backup | `pending_verification` | None confirmed | Offline |

## Evidence-aware facts

| Device alias | Fact | Value | confidence | source | last_verified |
|---|---|---|---|---|---|
| MAIN-PC | Memory capacity | Unknown | pending_verification | No current system evidence | not_verified |
| MAIN-PC | Intended role | Primary workspace | user_reported | User confirmation | 2026-01-15 |

## Verification queue

- [ ] Capture non-sensitive hardware facts from the operating system.
- [ ] Confirm the cloud workspace path and sync status.
- [ ] Confirm whether the configured model provider is local or remote.
