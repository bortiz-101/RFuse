[![Zotero Group](https://img.shields.io/badge/Zotero-Group_Library-CC2936)](https://www.zotero.org/groups/6363927/rfuse)

# RFuse

> **Status:** early-stage / in active development

## Goals
- Build a reproducible pipeline for RF fingerprinting experiments (capture → features → inference → evaluation)
- Support multi-sensor collection with a central fusion service (streaming + storage + telemetry)
- Keep results traceable to related research (paper-to-code references, experiments, and baselines)

## Architecture (planned)
- **agent-rs/** (Rust): capture/replay, windowing, feature/embedding extraction, streaming + telemetry
- **server-go/** (Go): ingestion (gRPC), storage, model/eval workflows, simple API + dashboard
- **proto/**: shared protobuf/gRPC contract


## License
Apache-2.0
