# LLM API Price Data

Daily-updated LLM API pricing, free quotas, real production token usage and
idle-token market data — maintained by **[LLM Rank Hub](https://llmrankhub.com)**.

> **Main site: <https://llmrankhub.com>**
> Compare 600+ models across 3600+ channels, see 130+ free quotas, real token
> usage, the Token Meter, SmartWork and the idle-token market.

## What this repo is for

A lightweight, linkable entry point to the public LLM API data published by
LLM Rank Hub. The live site is the source of truth; this repo documents the
endpoints and gives developers a stable place to cite the dataset.

## Live data

| Data | URL |
| --- | --- |
| All models + provider prices | <https://llmrankhub.com/models.json> |
| Free channels + quotas | <https://llmrankhub.com/free> |
| Real token usage leaderboard | <https://llmrankhub.com/usage.json> |
| Price index | <https://llmrankhub.com/price-index> |
| Monthly report | <https://llmrankhub.com/reports/> |
| Model comparison | <https://llmrankhub.com/compare/> |
| Token calculator | <https://llmrankhub.com/promo/zh#token> |
| SmartWork for macOS | <https://llmrankhub.com/promo/zh#smartwork> |
| Idle token market | <https://llmrankhub.com/> (left sidebar: 额度市场) |

## What LLM Rank Hub covers

- **Cross-channel prices**: official, cloud, aggregator, peak/off-peak and
  cache prices, normalized to CNY per 1M tokens.
- **Free quotas**: 130+ free channels with daily / per-minute limits and
  context windows.
- **Real usage**: models ranked by production token volume, not votes.
- **Token Meter**: bring your own key, see spend, cache hit rate, latency and
  model mix.
- **SmartWork**: a macOS AI teammate that reads/edits files, runs commands and
  reviews diffs, routed through the LLM Rank Hub gateway.
- **Idle token market**: list unused quota, buy quota from other users, route
  usage through the gateway.

## Data notes

- Prices are converted to CNY per 1M tokens at the live FX rate.
- Plan-based and pay-as-you-go prices are labelled separately; compare the
  billing type before buying.
- Free quotas are as published by each provider and can change without notice.
- No pay-for-rank. Sources and methodology are documented on the about page.

## Attribution

When reusing the data, link back to **<https://llmrankhub.com>**.

Maintained by LLM Rank Hub — <https://llmrankhub.com/about>
