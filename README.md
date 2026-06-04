### Hi, I'm Norbert

I build AI agent systems and crypto automation, mostly with Claude Code. I run a small team
of agents that operate my trading bots while I sleep, and I ship the tooling in the open.

**Agent payments stack on Arc** (Circle's stablecoin L1, USDC as gas)

A coherent set of pieces for letting AI agents move money safely:

- [arc-agent-guard](https://github.com/Mnorbert87/arc-agent-guard) gives an agent a wallet it can spend from autonomously, but only within policy: spend limits, an allowlist, an approval threshold, and a full audit trail
- [arc-conditional-pay](https://github.com/Mnorbert87/arc-conditional-pay) holds a USDC payment until a milestone is verified, then releases it
- [arc-streaming-pay](https://github.com/Mnorbert87/arc-streaming-pay) handles recurring and scheduled USDC payments (subscriptions, payroll, vesting)
- [arc-x402-agent](https://github.com/Mnorbert87/arc-x402-agent) lets an agent pay for x402-protected APIs on Arc, but only within policy
- [arc-x402-server](https://github.com/Mnorbert87/arc-x402-server) the seller side of x402 on Arc: charge USDC for an API and verify the payment
- [arc-event-hub](https://github.com/Mnorbert87/arc-event-hub) turns on-chain wallet activity into webhooks and automations
- [arc-testnet-mcp](https://github.com/Mnorbert87/arc-testnet-mcp) lets a Claude Code agent read balances and send USDC on Arc
- [arc-onboarding-kit](https://github.com/Mnorbert87/arc-onboarding-kit) takes you from nothing to a confirmed Arc transaction in minutes

**Other tools**

- [crypto-catalyst-scanner](https://github.com/Mnorbert87/crypto-catalyst-scanner) early bullish-momentum detector for the top-150 market-cap tokens
- [polymarket-opportunity-scanner](https://github.com/Mnorbert87/polymarket-opportunity-scanner) finds deep, tight, sub-3-cent prediction markets
- [agent-dashboard-mcp](https://github.com/Mnorbert87/agent-dashboard-mcp) exposes a multi-agent dashboard as MCP tools
- [claude-code-skills](https://github.com/Mnorbert87/claude-code-skills) reusable Claude Code skills

Everything here is MIT licensed. The safety-critical logic ships with deterministic tests.
