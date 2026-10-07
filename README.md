> **Payload** — Developer infrastructure for x402, agent payments, and programmable revenue.
> PAYLOAD → VEYLINE (flagship) → CALLX402 (action layer) → REVRULE (separate) → developer products → free utilities.
> This repo: **Veyline Developer Primer by Payload — formerly the x402 Paid API Starter Kit.**

# VEYLINE DEVELOPER PRIMER

*Charge AI agents per API call. The entry product from Payload (by Payload).*

[![Launched on Fazier](https://fazier.com/api/v1/public/badges/launch_badges.svg?badge_type=launched&theme=light)](https://fazier.com)

> **This repo is the product page.** The paid package ships to you when you buy; it is not open source. Buy links are below.

AI agents are starting to pay for API access over the x402 protocol. Every free "starter" out there is vendor lead-gen tied to one facilitator. This is the neutral, complete, paid kit: drop it into any Express API and start charging per call in an afternoon.

The Primer is the on-ramp. When you outgrow a starter kit and need production-grade x402 payments, the next step is **Veyline by Payload** — the production layer for x402 + MCP, built for autonomous economic control.

## Who it's for

Backend developers who run an Express API and want AI agents to pay per call — in an afternoon, without building payment infrastructure or signing up with a single facilitator.

## What you receive

The paid package ($79, one-time) includes:

- **Paid-route middleware** — unpaid requests get a 402 with machine-readable payment requirements; paid requests flow through. Each route sets its own asset and network (USDC default)
- **`/.well-known/x402` manifest generator** — for agent discovery and x402 bazaar listings
- **Two verifiers** — HMAC dev verifier for local testing, facilitator verifier for production (works with any x402 facilitator)
- **Append-only usage ledger (JSONL)** — every paid call, recorded
- **Facilitator-aware startup checks** — declare your facilitator's supported assets and networks; misconfigured routes fail at startup instead of at payment time
- **Working example server + 65 automated tests**, all passing (core flow, multi-asset, and facilitator-awareness verification)
- **README with a 5-minute quick start and a production checklist**

Non-custodial by design: the kit never holds private keys or touches funds. It only verifies that a payment happened, then serves the resource.

## What it does NOT include

- It is not the full Veyline platform. The Primer is the developer on-ramp; Veyline by Payload is the production layer.
- It does not collect payments on your behalf, hold keys, or settle funds. It verifies payment, then serves the resource.
- It does not build your API for you. You bring the Express API; the kit adds the paywall.

## Buy

**$79 one-time. Yours forever. No subscriptions, no lock-in.**

[Get the Veyline Developer Primer](https://payloadtools.gumroad.com/l/x402-paid-api-starter-kit)

Also on [Whop](https://whop.com/payload-f126/products/x402-paid-api-starter-kit-charge-ai-agents-per-api-call-in-usdc/)

**What happens after you get paid?** [RevRule by Payload](https://payloadtools.gumroad.com/l/revrule-by-payload) programs who earns what when your API makes money. x402 moves the money. RevRule determines the economics.
Also available: [x402 + MCP Monetization Kit bundle ($119)](https://payloadtools.gumroad.com/l/x402-mcp-bundle)

**License** — Single-seat commercial license, perpetual. Full text ships inside the package (LICENSE.txt). Not open source.

## Support and updates

- Support: kylers.partners@gmail.com
- Sold and supported by Payload. Small software that earns its keep.

---

**Payload** — small, sharp tools for developers.
Developer portal: https://payloadhq.github.io/ ·
All products: https://payloadtools.gumroad.com/ ·
Contact: kylers.partners@gmail.com
