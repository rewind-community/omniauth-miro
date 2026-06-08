# Changelog

## [1.0.7]

- Update transitive dependencies to address security vulnerabilities:
  - rack to 3.2.6 (GHSA-8vqr-qjwx-82mw, GHSA-v6x5-cg8r-vv6x, GHSA-v569-hp3g-36wr, GHSA-h2jq-g4cq-5ppq, GHSA-mxw3-3hh2-x2mh, GHSA-6xw4-3v39-52mm, GHSA-wpv5-97wm-hp9c, GHSA-w9pc-fmgc-vxvw, GHSA-p543-xpfm-54cp and related advisories)
  - jwt to 2.10.3 (GHSA-c32j-vqhx-rx3x)
  - faraday to 2.14.2 (GHSA-33mh-2634-fwr2, GHSA-5rv5-xj5j-3484)
  - uri to 1.1.1 (GHSA-j4pr-3wm6-xx2r)

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
