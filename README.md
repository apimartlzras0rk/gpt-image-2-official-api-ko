# gpt-image-2-official-api-ko — AI API 게이트웨이 (한국어)

> **One OpenAI-compatible key, 300+ models** · image2.5 **$0.0085/image** · Seedance 2.0 Mini **$0.01056/sec** · LLM from **$0.0228 / M tokens** · $1 minimum top-up.

**[요금 보기](https://go.apimart.ai/k-cde775)** · **[API 키 발급](https://go.apimart.ai/k-93f102)**

gpt-image-2-official-api-ko 는 하나의 `base_url` 과 하나의 키로 300+ 모델을 연결합니다. USD 결제, 종량 과금, 최소 $1 충전.

## Published unit prices (snapshot 2026-09-28)

| Unit | Price |
| --- | --- |
| `GPT Image 2.5 (1K)` | $0.0085 |
| `Seedance 2.0 Mini (480P/sec)` | $0.01056 |
| `Qwen3.7 Flash (per M input)` | $0.0228568 |

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"gpt-image-2.5-ext","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Keywords

`리버스` · `역설계` · `AI API 게이트웨이` · `API 중계` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

