# WoofyWalky — Project notes

## Purpose

Give prospective clients and hiring teams a concise, inspectable interface sample while keeping production implementation private. Product discovery is supported by the README; downloadable app releases are separate from source-code publishing.

## Scope

The private native iOS implementation includes onboarding, walk tracking, meal-photo flows, dog profiles, and health-record screens. Those integrations are intentionally excluded from this public sample.

## Technical choices

- One self-contained SwiftUI source file for easy review and integration into a new Xcode project.
- Reusable card/page composition instead of duplicated screens.
- Local state for preview interactions; nothing is persisted or transmitted.
- System text styles and semantic colours support Dynamic Type and system appearance. Device accessibility testing remains pending.
- No third-party dependencies or production endpoints.

## Verification

- Swift parser checks passed for the sample source. This checks syntax, not a complete build.
- Publication file allowlist, SVG parsing, and common secret-pattern checks passed.
- No Simulator or device build has been verified. Do not treat this sample as release-ready.
- No live integrations are included or tested.

## Release checklist

- [ ] Build in Xcode and test tabs, card sheets, large text, dark mode, and VoiceOver.
- [ ] Add screenshots captured from the running sample, labelled as sample UI.
- [ ] Add a verified App Store or public TestFlight link when available.
- [ ] Add an approved business contact for freelance and hiring enquiries.
- [ ] Keep all future commits free of production services, credentials, and personal data.
