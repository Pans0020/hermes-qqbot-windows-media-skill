# Hermes QQBot Windows Media Skill

Standalone Hermes/OpenCode-compatible skill for fixing and correctly operating QQBot media delivery on Pans0020's Windows Hermes setup.

## Skill

- [`SKILL.md`](./SKILL.md)

## Install in Hermes

```bash
hermes skills install --force --yes --category gateway https://raw.githubusercontent.com/Pans0020/hermes-qqbot-windows-media-skill/main/SKILL.md
```

## What it covers

- Why QQBot DM sends can fail with `频道不存在` / `40022001` / `11263`
- Correct QQ endpoint routing for DM, group, and channel targets
- Why `MEDIA:/mnt/c/...` and `MEDIA:/tmp/...` fail under a Windows gateway
- The `_normalize_local_media_path()` adapter fix pattern
- Regression tests and verification checklist
