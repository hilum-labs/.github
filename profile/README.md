# hilum-labs

Open source local LLM infrastructure for Node.js, browsers, React Native, and native apps.

`hilum-labs` builds local-first AI runtimes, WebGPU inference engines, JavaScript SDKs, React Native integrations, and native C/C++ model execution layers for running large language models on-device without cloud APIs.

## Local LLM Projects

- [`local-llm`](https://github.com/hilum-labs/local-llm): local LLM runtime for Node.js and server-side JavaScript.
- [`local-llm-browser`](https://github.com/hilum-labs/local-llm-browser): browser JavaScript SDK for local LLM inference with WebGPU.
- [`local-llm-browser-engine`](https://github.com/hilum-labs/local-llm-browser-engine): WebGPU inference engine for running LLMs directly in the browser.
- [`local-llm-rn`](https://github.com/hilum-labs/local-llm-rn): React Native package for on-device LLM inference on iOS and Android.
- [`local-llm-js-core`](https://github.com/hilum-labs/local-llm-js-core): shared JavaScript core for local AI runtimes and LLM SDKs.
- [`hilum-local-llm-engine`](https://github.com/hilum-labs/hilum-local-llm-engine): native C/C++ engine for high-performance local LLM inference.

## What We Build

- Local LLM runtimes for JavaScript, mobile, browser, and native environments.
- On-device inference engines focused on privacy, low latency, and practical deployment.
- WebGPU browser infrastructure for client-side LLM execution.
- Cross-platform SDKs that keep API design consistent across runtimes.
- Open source components for local AI, offline AI, and edge inference workflows.

## Why Local LLM Infrastructure

- No cloud dependency for core inference.
- Better privacy and data control.
- Lower latency for interactive AI apps.
- Platform-specific runtimes instead of one generic wrapper.
- Practical developer tooling for shipping local AI products.

## Repository Map

| Repository | Focus |
| --- | --- |
| [`local-llm`](https://github.com/hilum-labs/local-llm) | Node.js local LLM package |
| [`local-llm-browser`](https://github.com/hilum-labs/local-llm-browser) | Browser SDK for WebGPU LLM inference |
| [`local-llm-browser-engine`](https://github.com/hilum-labs/local-llm-browser-engine) | Browser inference engine and runtime core |
| [`local-llm-rn`](https://github.com/hilum-labs/local-llm-rn) | React Native local AI package |
| [`local-llm-js-core`](https://github.com/hilum-labs/local-llm-js-core) | Shared JavaScript runtime primitives |
| [`hilum-local-llm-engine`](https://github.com/hilum-labs/hilum-local-llm-engine) | Native C/C++ inference engine |

## Current Focus

- Expand the `local-llm` package family across Node.js, browser, and React Native.
- Build a dedicated WebGPU browser engine and browser SDK for local LLM inference.
- Keep local AI APIs consistent across JavaScript and native runtimes.
- Ship open source infrastructure for browser AI, on-device inference, and private model execution.
