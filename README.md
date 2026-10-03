# x402 Paid API Starter Kit
*Charge AI agents per API call in USDC. A commercial product by Payload (v1.0.1).*
> **Payload** — small, sharp tools for developers. Developer portal: https://payloadhq.github.io/


AI agents are starting to pay for API access with USDC over the x402 protocol. Every free "starter" out there is vendor lead-gen tied to one facilitator. This is the neutral, complete, paid kit: drop it into any Express API and start charging per call in an afternoon.

**What's inside the paid kit**
- Paid-route middleware: unpaid requests get a 402 with machine-readable payment requirements; paid requests flow through
- `/.well-known/x402` manifest generator for agent discovery (and x402 bazaar listings)
- Two verifiers: HMAC dev verifier for local testing, facilitator verifier for production (works with any x402 facilitator)
- Append-only usage ledger (JSONL) of every paid call
- Working example server + 9 automated tests, all passing
- README with a 5-minute quick start and a production checklist

Non-custodial by design: the kit never holds private keys or touches funds. It only verifies that a payment happened, then serves the resource.

**Buy** — $79 one-time. Yours forever. No subscriptions, no lock-in.
[Get the x402 Paid API Starter Kit](https://payloadtools.gumroad.com/l/x402-paid-api-starter-kit)
Also available: [x402 + MCP Monetization Kit bundle ($119)](https://payloadtools.gumroad.com/l/x402-mcp-bundle)

**License** — Single-seat commercial license, perpetual. Full text ships inside the package (LICENSE.txt). Not open source.

**Support** — kylers.partners@gmail.com

Sold by Payload. Small software that earns its keep.

---

**Payload** — small, sharp tools for developers.
Developer portal: https://payloadhq.github.io/ ·
All products: https://payloadtools.gumroad.com/ ·
Contact: kylers.partners@gmail.com
