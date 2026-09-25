# GPT Image 2 API 日本語ガイド（gpt-image-2 / gptimage2）

> 従量課金、最低 1 ドルから、OpenAI 互換エンドポイント。 **default $0.0085; 1K $0.0085; 2K $0.014**

**[模型页](https://apimart.ai/model) · [实时价格](https://apimart.ai/pricing) · [获取 API Key](https://apimart.ai/keys)**

## 料金（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `default` | $0.0085 |
| `1K` | $0.0085 |
| `2K` | $0.014 |
| `4K` | $0.021 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"gpt-image-2","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

本リポジトリはサードパーティ中継サービス APIMart の利用ガイドです。
