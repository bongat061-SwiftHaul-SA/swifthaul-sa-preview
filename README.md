# SwiftHaul SA — isolated GitHub Pages preview

This repository publishes a review-only static snapshot from the `design/uber-inspired-three-platform-ui-clean` branch of the main SwiftHaul SA repository.

It is intentionally separate from the production repository and does not deploy or modify production.

## Preview entry points

- Customer: `/customer.html`
- Driver: `/apps/driver/public/index.html`
- Company Admin: `/apps/company/public/index.html`

The static preview uses the existing public client assets. Server-side Netlify Functions are not hosted by GitHub Pages, so account operations that require those functions may not work in this preview.

## Source
https://github.com/bongat061-SwiftHaul-SA/swifthaul-sa/tree/design/uber-inspired-three-platform-ui-clean


Preview refresh trigger: Company Admin driver-approval staging fix (2026-11-17).
\n\nStaging preview refresh: Company Admin sign-up notification centre and corrected Driver/Company nested links (2026-11-17).\n
Staging preview refresh: complete driver onboarding form and admin application-profile review (2026-11-17).

Staging preview refresh: approved-driver selection, visible driver account IDs and copyable waybill references (2026-11-19).

Dispatch refinement: pending waybill suggestions added to the offer form (2026-11-19).

Preview refresh: driver approval validation feedback (2026-11-19).

Staging refresh: immediate driver application notification flow (2026-11-19).


<!-- staging-publish-source -->
Latest staging source fix: `96b9de027368bbcecf233d7f982f0769d6586aaf` (Driver post-login approval-banner DOM insertion). This preview is isolated from production.


<!-- Staging preview rebuild trigger: driver review details panel -->

<!-- refresh staging preview: driver review panel cache-bust -->

Preview refresh trigger: driver onboarding secure save-progress staging update (2026-11-19).
