### Hi, I'm a5768549 👋

Full-stack developer in Taiwan building **AI agents, automation workflows, MCP servers and AIGC video tooling**. Site: [wiretomind.com](https://wiretomind.com/)

#### Recent projects

| Project | What it is |
|---|---|
| [codex-token-shower](https://github.com/a5768549/codex-token-shower) | Local dashboard for Codex / ZCode token usage — Windows floating widget and browser view, reads local SQLite only, no API key |
| [model-worker-mcp](https://github.com/a5768549/model-worker-mcp) | MCP server that delegates bounded coding tasks to an OpenAI-compatible model: explicit read/write paths, diff validation before `git apply`, risk-based routing |
| [claude-joint-decision](https://github.com/a5768549/claude-joint-decision) | Codex plugin (MCP + skill): a read-only Claude second opinion before a change and a diff review after it |
| [videoeditor (Kimu fork)](https://github.com/a5768549/videoeditor) | Kimu with final H.264 export rendered on Alibaba Cloud Function Compute — private OSS assets, Remotion custom container, idempotent per-job locks |
| [llm-tpm-pacer](https://github.com/a5768549/llm-tpm-pacer) | Fair-share tokens-per-minute pacer for LLM upstreams: requests queue instead of getting HTTP 429, each conversation gets an equal share |
| [verify-asar-deps](https://github.com/a5768549/verify-asar-deps) | Fails an Electron build when a package inside `app.asar` cannot resolve its dependencies (the pnpm + electron-builder launch crash) |
| [electron-updater-strict-authenticode](https://github.com/a5768549/electron-updater-strict-authenticode) | Fail-closed Windows Authenticode check for electron-updater; the built-in one accepts updates when PowerShell cannot verify them |
| [uvc-ptz-win](https://github.com/a5768549/uvc-ptz-win) | Pan / tilt / zoom control for USB PTZ cameras on Windows, one PowerShell file |

#### Open-source contributions

- **DeepSeek Harness** — fix for historical session revisions being invalidated by unrelated writes ([#8783](https://github.com/deepseek-ai/deepseek-harness/discussions/8783#discussioncomment-19048549)), and reasoning levels for unlisted models on shipped provider routes ([#4071](https://github.com/deepseek-ai/deepseek-harness/discussions/4071#discussioncomment-19048550))
- **VectCutAPI** — configurable timeline frame rate for `create_draft` ([#88](https://github.com/sun-guannan/VectCutAPI/pull/88))
- **dsh-image-gen** — load the image tools on headless, ACP and SDK profiles that have no web server ([#85](https://github.com/shanliuling/dsh-image-gen/pull/85))
- **dsh-token-usage-dashboard** — rescan double-counting, unauthenticated routes and `DSH_HOME` handling ([#1](https://github.com/solstice621/dsh-token-usage-dashboard/issues/1))

#### Stack

TypeScript · Node.js · React · Electron · Python · PostgreSQL · Redis · Alibaba Cloud (FC, OSS) · FFmpeg · Remotion · MCP

<sub>Earlier work: Arduino / ESP32 / Raspberry Pi projects and Ethereum (geth) tutorials — see the repositories list.</sub>
