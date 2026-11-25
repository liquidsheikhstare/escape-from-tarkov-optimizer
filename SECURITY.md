# Security Policy

## Scope

Tarkov FPS Optimizer is a local Windows utility. Its entire scope is limited to:

- Your local *Escape from Tarkov* graphics / game configuration files.
- Your local shader and DirectX cache directories.
- Timestamped backups of those files, stored next to the tool.

## Explicitly out of scope

The tool does **not**:

- Inject DLLs, hook processes, or patch game files.
- Read from or write to game memory.
- Modify, replace or interact with any anti-cheat component.
- Open network connections, phone home, or send telemetry.
- Install services, drivers, or auto-start entries.
- Require an account, subscription or activation.

## Backups

Before writing any change, the tool creates a timestamped copy of the settings it is about to modify. You can restore a backup at any time from within the tool, and you can always restore manually by copying the backup files back to their original location.

## Reporting a vulnerability

If you believe you have found a security issue, please open a private report on the project's GitHub page rather than a public issue. Include your Windows version, the steps to reproduce, and any relevant logs. Please do not include personal information or game account credentials.

## Supported versions

| Version | Supported |
| --- | --- |
| 1.0.0 | Yes |
