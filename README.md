# Requests-Zig

> Part of the [crawler-requests](https://github.com/crawler-requests) family — a convenient `requests`-style HTTP client for **Zig**, built for crawlers and anti-bot scenarios.

**Requests-Zig** 是 [crawler-requests](https://github.com/crawler-requests) 家族中 **Zig** 语言的 HTTP 客户端，API 风格参考 Python 的 [`requests`](https://github.com/psf/requests)，内置 TLS / HTTP2 / JA3 / JA4 指纹定制能力，面向爬虫与反检测场景。

## 特性

- 简洁、`requests` 风格的 API
- 支持 HTTP / HTTPS / HTTP2
- 支持 JA3 / JA4 / TLS 指纹自定义
- （更多能力开发中）

## 安装

<!-- TODO: Zig 包管理器安装方式 -->

## 快速上手

<!-- TODO: Zig 示例代码 -->

```zig
// 伪代码示意，最终 API 以实现为准
// resp = requests.get("https://example.com", ja3="chrome120")
// print(resp.status_code, resp.text)
```

## 状态

🚧 规划中 / 早期开发（scaffold）。欢迎在 Issues 讨论 API 设计与参与实现。

## 相关

- 引擎库：[requests-go](https://github.com/crawler-requests/requests-go)（Go，uTLS）
- 指纹评测：[tls-fingerprint-benchmark](https://github.com/crawler-requests/tls-fingerprint-benchmark)
- 家族其他语言：见组织主页 <https://github.com/crawler-requests>

## License

Apache-2.0
