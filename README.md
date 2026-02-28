XELVYN
Autonomous Execution. Collective Control.

Web4 autonomous agent deployment platform. Deploy, manage, and scale software agents that operate independently on-chain -- with x402 USDC micropayments on Base and XMTP encrypted messaging.

What We Build
XELVYN provides the infrastructure for deploying autonomous software agents to isolated VPS instances. Each agent operates independently: paying for compute and data via the x402 Protocol (USDC on Base), communicating with operators through end-to-end encrypted XMTP channels, and executing configurable strategies 24/7.

Packages
Package	Description	Install
@xelvyn/cli	Command-line interface for agent deployment and management	npm install -g @xelvyn/cli
@xelvyn/sdk	TypeScript SDK for programmatic agent control	npm install @xelvyn/sdk
@xelvyn/skills	Pre-built agent capabilities (DeFi, Security, Data, Infra)	xelvyn skill install <name>
Quick Start
npm install -g @xelvyn/cli
xelvyn login
xelvyn init my-agent --template yield --network base
xelvyn skill install yield-rebalancer --ai openai
xelvyn deploy --x402 --xmtp
Stack
Base (8453) USDC x402 Protocol XMTP v3 TypeScript Node.js

Links
Platform
Documentation
Skills Library
X / Twitter
MIT Licensed
