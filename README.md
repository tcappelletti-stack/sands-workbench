# sands-workbench

Live prototypes for the **Workbench** area of *entwickler intelligence* (entwickler.de / SandS Media).

Root is the prototype. Everything under `flows/` is an annotated user-flow prototype.

| Path | What it is | Link |
|---|---|---|
| `/` | **Workbench v8** — the 3-panel workspace. LEFT = "Sources in focus" (the user's workspace, checked = in focus this turn), CENTRE = chat with inline citation chips, RIGHT = retrieved Sources / Agents. | [open](https://tcappelletti-stack.github.io/sands-workbench/) |
| `/flows/epic1/` | **Epic 1** — Composer user flows (web + native). Assembling sources in the composer: chips, the transient "In focus (N)" pill, add/remove paths. | [open](https://tcappelletti-stack.github.io/sands-workbench/flows/epic1/) |
| `/flows/epic2/` | **Epic 2** — Sources-in-focus grounding. Graduates the focus set into a persistent left panel and makes that focus legible in the conversation. | [open](https://tcappelletti-stack.github.io/sands-workbench/flows/epic2/) |

All prototypes are self-contained single-file HTML — no build, no install, no login.

**All prototypes:** [sands-prototypes](https://tcappelletti-stack.github.io/sands-prototypes/)

## Notes

- A **POC** = a Piece of Content (article, talk recording, magazine issue, tutorial).
- Prototypes are design artefacts, not production code — they mock data and interactions to make the intended behaviour unambiguous. Where a flow and the current build disagree, the flow is the request.

## Updating

Replace the relevant `index.html` and commit. GitHub Pages redeploys automatically.
