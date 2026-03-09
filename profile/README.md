# hilum-labs

Local-first LLM runtimes for JavaScript, mobile, browser, and native platforms.

We build practical inference engines and SDKs that run on-device, stay close to the host platform, and expose clean developer APIs.

## Start Here

- [`local-llm`](https://github.com/hilum-labs/local-llm): Node.js package for running LLMs locally.
- [`hilum-local-llm-engine`](https://github.com/hilum-labs/hilum-local-llm-engine): low-level inference engine in C/C++.

## Platform Direction

- Node.js: production package available today.
- React Native: package family work is in active development.
- Browser: `local-llm-browser-engine` and `local-llm-browser` are the next major workstream.
- Native: low-level engine work continues in C/C++.

## Why This Exists

- Local execution instead of hosted inference APIs.
- Cross-platform package family with platform-specific runtimes.
- Practical SDKs and engines, not demo wrappers.
- Privacy by default: model execution stays on the device.

## Public Repositories

| Repository | Purpose |
| --- | --- |
| [`local-llm`](https://github.com/hilum-labs/local-llm) | Main Node.js package and umbrella package family entry point |
| [`hilum-local-llm-engine`](https://github.com/hilum-labs/hilum-local-llm-engine) | Native engine implementation in C/C++ |

## Current Focus

- Strengthen the `local-llm` package family.
- Split browser work into `local-llm-browser-engine` and `local-llm-browser`.
- Keep APIs consistent across Node.js, React Native, browser, and native layers.

## Status

Active development. Browser engine and browser SDK repositories are being prepared.
