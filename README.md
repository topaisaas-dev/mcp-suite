# @topaisaas/mcp-suite

> **Unified Model Context Protocol (MCP) Server for the TopAI Sovereign Appliance Suite.**  
> Exposes 9 high-performance, deterministic developer tools natively to Claude Desktop, Cursor, and Windsurf via standard JSON-RPC 2.0 stdio — **sub-30ms execution, zero LLM token burn**.

[![npm version](https://img.shields.io/npm/v/@topaisaas/mcp-suite.svg)](https://www.npmjs.com/package/@topaisaas/mcp-suite)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](LICENSE)
[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-purple.svg)](https://modelcontextprotocol.io)
[![USD Checkout](https://img.shields.io/badge/14--Day%20Money--Back-Guarantee-FFD600.svg)](https://topaigateway.com/audit?utm_source=npm&utm_campaign=mcp_suite)

---

## ⚡ 1-Click Integration in Claude Desktop or Cursor

Add this to your `claude_desktop_config.json` or `.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "topai-suite": {
      "command": "npx",
      "args": ["-y", "@topaisaas/mcp-suite"]
    }
  }
}
```

### Need 19 Cloud-Edge Deterministic MCP Tools Too?
Pair this local appliance suite with our canonical 19-tool Edge MCP Server (`@topaisaas/mcp-server`):

```json
{
  "mcpServers": {
    "topai-edge": {
      "command": "npx",
      "args": ["-y", "@topaisaas/mcp-server"]
    }
  }
}
```

---

## 🔍 Free Interactive Diagnostics & Sample Previews (No Signup Required)

- **Interactive FinOps Token Bleed Auditor**: Estimate your monthly LLM token waste and get a deterministic pruning blueprint in 10 seconds -> [**Run Free FinOps Audit**](https://topaigateway.com/audit?utm_source=npm&utm_campaign=mcp_suite)
- **Cursor & Claude Code Sovereign Rules Preview**: Inspect our production `.cursorrules` / `CLAUDE.md` starter -> [**Preview Sample Rules**](https://topaigateway.com/download/samples/topai-cursor-rules.txt?utm_source=npm&utm_campaign=mcp_suite)
- **n8n Sovereign Workflow Starter Preview**: Inspect a ready-to-import deterministic JSON workflow -> [**Preview n8n Starter**](https://topaigateway.com/samples/topai-n8n-starter.json?utm_source=npm&utm_campaign=mcp_suite)

---

## 💳 Hero Quartet — Direct USD Checkout (14-Day No-Questions-Asked Money-Back Guarantee)

All TopAI toolkits and API plans are billed transparently in **USD ($)** via our edge checkout and backed by an unconditional **14-Day No-Questions-Asked Money-Back Guarantee**.

| Plan / Toolkit | USD Price | What You Unlock | Instant Direct Checkout |
| :--- | :--- | :--- | :--- |
| **Pack 1: DevEx & FinOps Pro Trial** | **$0 / 7 Days** | 10,000 req/mo across 100+ sub-30ms deterministic edge APIs (`$14/mo` after trial, cancel anytime) | [**Start $0 7-Day Trial →**](https://topaigateway.com/checkout?pack=pack_1_devex&direct=true&utm_source=npm&utm_medium=readme&utm_campaign=mcp_suite) |
| **n8n & Make 65-Workflow Super-Pack** | **$19 Once** | 65 production-hardened n8n & Make automation templates with zero-token edge connectors | [**Get Super-Pack ($19) →**](https://topaigateway.com/checkout?pack=bundle_n8n_make&direct=true&utm_source=npm&utm_medium=readme&utm_campaign=mcp_suite) |
| **Runaway Token Breaker Shield** | **$29 Once** | Deterministic circuit-breaker kit to stop infinite agent loops & runaway LLM API bills | [**Get Breaker Shield ($29) →**](https://topaigateway.com/checkout?pack=runaway_token_breaker&direct=true&utm_source=npm&utm_medium=readme&utm_campaign=mcp_suite) |
| **Cursor & Claude Code 169-Tool Harness Kit** | **$49 Once** | Complete 169-tool sovereign engineering harness, offline keys, hooks & CI/CD guardrails | [**Get 169-Tool Kit ($49) →**](https://topaigateway.com/checkout?pack=bundle_cursor_harness&direct=true&utm_source=npm&utm_medium=readme&utm_campaign=mcp_suite) |

---

## 🛠️ The 9 Built-in Local Developer Tools

| MCP Tool Name | Description |
| :--- | :--- |
| `agentpr_guard_audit` | Audits git diffs for AI hallucinations, typosquatting & architectural leaks. |
| `tokenprune_wasm_trim` | Prunes source code AST to save 50%-70% of prompt tokens in LLMs. |
| `dockerlean_wasm_audit` | Audits Dockerfile for 12 layer bloat anti-patterns and security risks. |
| `sqltwin_stream_anonymize` | Anonymizes SQL dumps preserving 100% of foreign keys and unique constraints. |
| `terracost_blast_evaluate` | Air-gapped blast radius & monthly FinOps cost delta for Terraform plans. |
| `flaky_quarantine_analyze` | Markov chain flaky test detection and automated Playwright/Jest isolation. |
| `pack3d_wasm_pack` | 3D extreme point container packing and volumetric weight calculation. |
| `cidr_shield_lookup` | Microsecond threat & cloud datacenter IP range detection. |
| `edgarpulse_parse_filing` | Deterministic SEC Form 4 and Form 8-K insider cluster buying alpha engine. |

---

## 🛡️ License & Quota Tollbooth

TopAI Sovereign MCP Suite comes with an out-of-the-box **Free Sandbox of 25 tool runs**, enabling immediate zero-friction evaluation directly inside Claude Desktop, Cursor, or Windsurf.

### Activating Unlimited Pro / Harness Access
To unlock unlimited offline runs for production pipelines, developer environments, or CI/CD:
1. Choose a USD plan or one-time kit from the [Hero Quartet above](#-hero-quartet--direct-usd-checkout-14-day-no-questions-asked-money-back-guarantee) (backed by our **14-Day No-Questions-Asked Money-Back Guarantee**).
2. Inject your instant Ed25519 offline license key into your environment or MCP client config:

```json
{
  "mcpServers": {
    "topai-suite": {
      "command": "npx",
      "args": ["-y", "@topaisaas/mcp-suite"],
      "env": {
        "TOPAI_LICENSE_KEY": "TOPAI-PRO-XXXXXXXXXXXXXXXX"
      }
    }
  }
}
```

### Emergency 24-Hour Production Grace Bypass
If a production pipeline exceeds its quota unexpectedly during an active incident:
```bash
export TOPAI_EMERGENCY_GRACE=1
```
This grants a 24-hour non-blocking bypass so builds never fail during release freezes.

---

## 📄 License

Apache-2.0. Copyright (c) 2026 TopAI Sovereign Studio · [topaigateway.com](https://topaigateway.com)
