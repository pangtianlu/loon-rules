# Loon rules

Krak / Kraken / UK PayPal remote rules for Loon.

## Subscribe (recommended)

```text
https://raw.githubusercontent.com/pangtianlu/loon-rules/main/UK-Krak-PayPal.list
```

Loon: Configuration → Rules → Subscribe → Add

- URL: the link above
- Policy: your UK node or group name
- Tag: `UK-Krak-PayPal`

Config snippet:

```ini
[Remote Rule]
https://raw.githubusercontent.com/pangtianlu/loon-rules/main/UK-Krak-PayPal.list, policy=英国, tag=UK-Krak-PayPal, enabled=true
```

Replace `英国` with your real policy name.

## Separate lists

- Krak + Kraken: `https://raw.githubusercontent.com/pangtianlu/loon-rules/main/UK-Krak-Kraken.list`
- PayPal only: `https://raw.githubusercontent.com/pangtianlu/loon-rules/main/UK-PayPal.list`
