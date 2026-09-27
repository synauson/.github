# synauson

**synauson** is a multi-conference audio media server built on GStreamer and ONNX Runtime. It handles WebRTC and SIP conferencing, real-time voice activity detection, and end-of-turn inference — distributed as a licensed container image that runs at your edge.

## Repositories

| Repo | Description |
|------|-------------|
| [jsyn](https://github.com/synauson/jsyn) | Java client library — in-process JNI binding to the synauson runtime. Open source, Apache 2.0. |
| [examples](https://github.com/synauson/examples) | Reference applications. WebRTC testbed, Windows quickstart, and more. Open source, Apache 2.0. |

## Distribution model

**synauson server** is proprietary, license-checked software distributed as a container image (`cr.synauson.com/synauson/synauson-server`). Contact [synauson.com](https://synauson.com) for licensing.

**Client SDKs** (jsyn and future language adapters) are open source under Apache 2.0. They wrap the synauson gRPC API and the in-process JNI interface. Compiled native artifacts (`jsyn-natives-linux`, `jsyn-natives-windows`) are distributed as pre-built binaries from the public Synauson Maven repository (`https://maven.synauson.com/releases`).

## Getting started

See **[jsyn](https://github.com/synauson/jsyn)** for installation and the quick-start guide, or browse the **[examples](https://github.com/synauson/examples)** for complete reference applications.
