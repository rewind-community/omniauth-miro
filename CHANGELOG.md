# Changelog

## [1.0.9]

- Address transitive dependency security advisories by updating `Gemfile.lock`:
  - `rack` 3.1.16 → 3.1.21 (GHSA-8vqr-qjwx-82mw, GHSA-v6x5-cg8r-vv6x, GHSA-h2jq-g4cq-5ppq, GHSA-v569-hp3g-36wr, GHSA-mxw3-3hh2-x2mh, GHSA-6xw4-3v39-52mm, GHSA-wpv5-97wm-hp9c, GHSA-w9pc-fmgc-vxvw, GHSA-p543-xpfm-54cp, and related multipart/host/static advisories)
  - `faraday` 2.13.1 → 2.14.3 (GHSA-98m9-hrrm-r99r, GHSA-5rv5-xj5j-3484, GHSA-33mh-2634-fwr2)
  - `jwt` 2.10.1 → 2.10.3 (GHSA-c32j-vqhx-rx3x)
  - `json` 2.12.2 → 2.19.9 (GHSA-x2f5-4prf-w687)
  - `uri` 1.0.3 → 1.0.4 (GHSA-j4pr-3wm6-xx2r)

## [1.0.8]

- Fix the `tag-and-release` workflow to create the release tag with the `rewind-community-tagger` GitHub App token (`TAGGER_APP_ID`/`TAGGER_PRIVATE_KEY`) instead of the default `GITHUB_TOKEN`

## [1.0.7]

- Address CVE-2026-54603 by updating oauth2 to 2.0.25

## [1.0.6]

- Update Ruby version to 3.4.5 to address security vulnerabilities

## [1.0.5]

- Address CVE-2025-49007
- Update dependencies

## [1.0.4]

- Address CVE-2025-27221 by updating uri to 1.0.3
- Update other dependencies to their respective latest minor versions

## [1.0.3]

- Remove overwritten callback_phase method that skipped refresh_token existence check

## [1.0.2]

- Update uid to use organization id id
- Added token response into omniauth hash
- Overwrite callback_phase method to not fail upon missing refresh token

## [1.0.1]

- Bugfix: added client secret to token params request
- Updated to full url for context endpoint

## [1.0.0]

- New omniauth-miro strategy for Miro OAuth 2.0
