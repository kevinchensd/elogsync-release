# ELogSync Personal release distribution policy

## Scope

This branch is the public GitHub Release entry for ELogSync Personal.

Public documentation is limited to product download pages, release indexes, release notes, and this policy. Installer files are uploaded only as GitHub Release assets.

Never commit or upload databases, user attachments, API keys, license configuration, user configuration, crash dumps, or build caches.

All user-facing download guidance, release indexes, and release notes must be bilingual in Simplified Chinese and English, with Chinese presented first.

## Tags and releases

Use the Personal-prefixed tag for every public release:

| Product | Tag format | Release title |
| --- | --- | --- |
| Personal | `personal-v<version>` | `ELogSync Personal v<version>` |

The distribution tag identifies one public release record.

## Assets

Asset names use the following form:

```text
ELogSync-Personal-v<version>-windows-x64-setup.exe
ELogSync-Personal-v<version>-macos-universal.dmg
```

Publish only installers that passed their product's local build, installation, launch, exit, and data-retention checks. A release note must state each asset's SHA-256, supported platform, installer type, stability, changes, upgrade/backup reminder, and known limitations.

## Stable and pre-release status

- Mark a release stable only after its product's final acceptance and installer regression pass.
- Mark testing builds as pre-releases, with the test purpose and limitations stated in both Chinese and English.
- Keep the Personal version index and release notes under `docs/personal/`.
