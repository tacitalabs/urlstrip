# URLStrip 1.4.0 Build 30

URLStrip 1.4.0 Build 30 expands desktop clipboard cleaning while preserving the surrounding content people actually copied.

## What changed

- Cleans supported URLs inside multi-line text while preserving prose, punctuation, wrappers, Unicode, and line endings.
- Preserves native clipboard representations on macOS and native Unicode text on Windows.
- Keeps Command Guard ahead of clipboard modification and preserves exact restore behavior.
- Adds fail-closed signed rule-feed verification and visible rule, catalog, and app update status.
- Preserves supported Amazon short-link resolution and adds tested Airbnb query-boundary handling.
- Keeps privacy redirects explicit and fail-closed.

## Downloads and trust

- The universal macOS DMG is Developer ID signed, Apple notarized, and stapled.
- The Windows x64 installer, application, and CLI are Azure Trusted Signing signed and timestamped.
- Both artifacts passed native installation, runtime, uninstall, and data-restoration acceptance for their recorded scope.

## Verification limitations

Windows catalog tray navigation and the transient live pending indicator remain waived and unverified for this release. They are not recorded as passing checks, and no product defect was confirmed. Rules tray navigation and the observed Command Guard warning-priority scenario passed.
