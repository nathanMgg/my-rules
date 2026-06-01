# my-rules

统一规则仓库，用于同时维护 OpenClash、Quantumult X、Shadowrocket 可共用的 Classical 规则列表。

## 规则格式

本仓库采用通用 Classical 格式，避免针对单个平台定制：

```text
DOMAIN-SUFFIX,example.com
DOMAIN-KEYWORD,example
```

## 文件说明

| 文件 | 内容 |
| --- | --- |
| `AI.list` | AI 服务规则：OpenAI、ChatGPT、Anthropic、Claude、Gemini、xAI、Grok、OpenRouter、Cursor、Perplexity、Groq、Copilot、Meta AI |
| `Twitter.list` | Twitter / X 相关域名规则 |
| `YouTube.list` | YouTube 相关域名规则 |
| `Telegram.list` | Telegram 相关域名规则 |
| `Apple.list` | Apple / iCloud / iTunes 相关域名规则 |

## 使用方式

将对应 `.list` 文件的 raw 链接添加到 OpenClash、Quantumult X 或 Shadowrocket 的规则配置中即可。
