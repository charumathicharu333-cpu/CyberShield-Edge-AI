# CyberShield Edge AI

Privacy-preserving, local-first cybersecurity assistant prepared for a Snapdragon AI Lab Build & Present demonstration.

## Run locally

1. Open a Command Prompt in this folder.
2. Run `py -m http.server 8000`.
3. Open <http://localhost:8000/>.

No build step, package manager, database, cloud account, or API key is required for this preview.

## What is implemented

- Dashboard with security status, threat overview, timeline, graph, privacy meter, and recommended actions
- Local monitor filters and search
- Transparent rule-based threat correlation with no fabricated confidence percentage
- Interactive Attack DNA graph with event detail inspection
- Human-readable Threat Story scenarios
- Attack Chain Replay with play, previous, next, and restart controls
- Cyber Twin demo model clearly marked as sample data
- Risk heatmap by component and time
- Privacy Center with accurate preview data boundaries
- Edge Health page that reports browser-observable metrics only
- Defensive Response Planner with notes and safe checklist actions
- Evidence Vault using the browser Web Crypto API for SHA-256 evidence hashes
- Local Security Assistant using deterministic retrieval/rule fallback
- JSON and HTML incident report export
- Local browser persistence with reset controls

## Honest boundaries

This package runs on sample cybersecurity events in DEMO MODE. It does not access the host operating system, claim Snapdragon/NPU performance, claim Qualcomm AI Hub integration, or send telemetry to a cloud service. No destructive remediation commands are included.

The architecture is intentionally modular in `index.html`: sample logs flow through event normalization, risk rules, correlation, graph visualization, explanation, response planning, evidence preservation, and export. A future `LocalModel` adapter can be added for ONNX, TensorFlow Lite, PyTorch, or Qualcomm AI Hub models after measured integration.

## Technology

- HTML, CSS, and browser JavaScript
- Browser Web Crypto API for evidence hashing
- LocalStorage for demo workspace persistence
- No external runtime dependencies

## Future improvements

- Add an opt-in Windows Event Log and process/network connector
- Add a local model adapter with measured inference timing
- Add a signed evidence manifest and immutable append-only storage
- Add a backend for multi-user review workflows
- Add Snapdragon CPU/GPU/NPU measurements after hardware validation

## License

MIT License. Use and adapt for your demonstration.
