# DA4 Hermes Demo Pilot Hardening

## Overview
- Status: complete
- Goal: make the existing static Hermes Agent demo stronger for pilot/showcase use after DA1 MVP hardening.
- Scope: keep the current no-build HTML demo, add pilot-ready interaction polish, audit trail, print/export, and docs.

## Tasks
- [x] Add human-in-the-loop audit log visible in the demo.
- [x] Add print/export controls for generated documents.
- [x] Make approval state and workflow completion clearer.
- [x] Remove fragile inline event dependency and escape free-text chat input.
- [x] Export the currently edited document body with basic HTML sanitization.
- [x] Update README run/verification notes.
- [x] Verify the static HTML opens without syntax/runtime issues.

## Success Criteria
- Existing scenario flow still works.
- Approval cannot run before a document is generated.
- Demo records visible audit events for scenario, agent completion, approval, print/export.
- Static demo remains runnable by opening `demo/index.html`.
- Free-text input is rendered as text, not raw HTML.
- Export uses the document currently shown in the editor.

## Unresolved Questions
- Browser automation screenshot QA was not completed because Playwright is not installed in this repo.

## Verification
- `node --check` on extracted inline script: passed.
- Python `HTMLParser` parse of `demo/index.html`: passed.
- Temporary local server returned `HTTP/1.0 200 OK` for `/demo/index.html` on port `8094` and was stopped.
- Playwright browser automation attempted but failed because the `playwright` package is not installed.
