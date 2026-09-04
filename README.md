# Loon rules

Krak / Kraken / UK PayPal remote rules, plus AI challenge helpers.

## Subscribe

### Krak + Kraken + PayPal → UK

```text
https://raw.githubusercontent.com/pangtianlu/loon-rules/main/UK-Krak-PayPal.list
```

Policy: `英国手动策略`

### AI Cloudflare / Arkose challenge → same as AI (US)

```text
https://raw.githubusercontent.com/pangtianlu/loon-rules/main/AI-Challenge.list
```

Policy: `美国手动策略` (must match your AI-Global policy)

Place this **above** ad-blocking rules so `challenges.cloudflare.com` is not rejected.

## Config snippet

```ini
[Remote Rule]
https://raw.githubusercontent.com/VPSDance/ai-proxy-rules/main/rules/loon/global.list, policy=美国手动策略, tag=AI-Global, enabled=true
https://raw.githubusercontent.com/pangtianlu/loon-rules/main/AI-Challenge.list, policy=美国手动策略, tag=AI-Challenge, enabled=true
https://raw.githubusercontent.com/pangtianlu/loon-rules/main/UK-Krak-PayPal.list, policy=英国手动策略, tag=UK-Krak-PayPal, enabled=true
```
