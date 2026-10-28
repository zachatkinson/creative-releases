# Creative Releases

Built release zips and update manifests for Creative Branding's WordPress plugins. Source code lives in private repos; nothing here is edited by hand.

- `creative-tracking/info.json`: the latest Creative Tracking release. Sites running the plugin read it (the `Update URI` header) to offer updates, and check each zip against its SHA-256.
- Releases: one per version, tagged `<plugin>-<version>`, with the zip attached.

Published by each plugin's `.github/workflows/release.yml` on a version tag.
