# hilum-labs

Local-first LLM runtimes for JavaScript, mobile, and native platforms.

We build practical inference packages that run on-device, stay close to the host platform, and expose clean developer APIs.

## Start Here

- [`local-llm`](https://github.com/hilum-labs/local-llm): Node.js package for running LLMs locally.
- [`local-llm-rn`](https://github.com/hilum-labs/local-llm-rn): React Native package for on-device LLM inference.
- [`hilum-local-llm-engine`](https://github.com/hilum-labs/hilum-local-llm-engine): low-level C/C++ inference engine.
- [`local-llm-js-core`](https://github.com/hilum-labs/local-llm-js-core): shared JavaScript runtime primitives.

## Platform Direction

- Node.js: production package available today.
- React Native: platform package in active development.
- Browser: `local-llm-browser-engine` and `local-llm-browser` are the next major workstream.
- Native: low-level engine work continues in C/C++.

## Why This Exists

- Local execution instead of hosted inference APIs.
- Cross-platform package family with platform-specific runtimes.
- Practical SDKs and engines, not demo wrappers.
- Privacy by default: model execution stays on the device.

## Repository Map

| Repository | Purpose |
| --- | --- |
| [`local-llm`](https://github.com/hilum-labs/local-llm) | Main Node.js package and umbrella package family entry point |
| [`local-llm-rn`](https://github.com/hilum-labs/local-llm-rn) | React Native integration layer |
| [`local-llm-js-core`](https://github.com/hilum-labs/local-llm-js-core) | Shared JavaScript core components |
| [`hilum-local-llm-engine`](https://github.com/hilum-labs/hilum-local-llm-engine) | Native engine implementation in C/C++ |

## Current Focus

- Strengthen the `local-llm` package family.
- Split browser work into `local-llm-browser-engine` and `local-llm-browser`.
- Keep APIs consistent across Node.js, React Native, browser, and native layers.

## Status

Active development. The browser engine and browser SDK are being prepared as dedicated repositories.
