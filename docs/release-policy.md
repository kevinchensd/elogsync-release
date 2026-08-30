# Release distribution policy

## Scope

`kevinchensd/elogsync-release` is the only public GitHub Release repository for ELogSync Personal and ELogSync Enterprise. It is a distribution record, not an application source repository.

Allowed Git content is limited to public release documentation: product download pages, release indexes, release notes, and this policy. Installer files are uploaded only as GitHub Release assets.

Never commit or upload application source code, databases, user attachments, API keys, license configuration, user configuration, crash dumps, or build caches.

All user-facing download guidance, release indexes, and release notes must be bilingual in Simplified Chinese and English, with Chinese presented first.

## Tags and releases

Use one product-prefixed tag for every public release:

| Product | Tag format | Release title |
| --- | --- | --- |
| Personal | `personal-v<version>` | `ELogSync Personal v<version>` |
| Enterprise | `enterprise-v<version>` | `ELogSync Enterprise v<version>` |

The distribution tag identifies a release record only. It is not a source-code tag. Exact application source, when access is authorized, is obtained from the matching tag in that product's source repository.

## Assets

Asset names use the following form:

```text
ELogSync-Personal-v<version>-windows-x64-setup.exe
ELogSync-Personal-v<version>-macos-universal.dmg
ELogSync-Enterprise-v<version>-windows-x64-setup.exe
ELogSync-Enterprise-v<version>-macos-arm64.dmg
```

Publish only installers that passed their product's local build, installation, launch, exit, and data-retention checks. A release note must state each asset's SHA-256, supported platform, installer type, stability, changes, upgrade/backup reminder, and known limitations.

GitHub automatically displays ZIP and TAR.GZ snapshots for every Release tag. Those archives contain only this distribution repository's public documentation and cannot be disabled per Release.

## Stable and pre-release status

- Mark a release stable only after its product's final acceptance and installer regression pass.
- Mark testing builds as pre-releases, with the test purpose and limitations stated in both Chinese and English.
- Keep Personal and Enterprise version indexes separate even when their version numbers coincide.
