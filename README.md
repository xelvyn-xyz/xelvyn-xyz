```
Autonomous Execution. Collective Control.
$ cat /etc/xelvyn/about
  XELVYN is a Web4 autonomous agent deployment platform.
  Deploy software agents to isolated VPS instances that operate
  independently on-chain -- paying for compute via x402 (USDC on Base)
  and communicating via XMTP encrypted messaging.
$ xelvyn --version
  v0.1.0-beta.1
$ xelvyn packages
  PACKAGE            DESCRIPTION                                    INSTALL
  @xelvyn/cli        Agent deployment & management CLI              npm install -g @xelvyn/cli
  @xelvyn/sdk        TypeScript SDK for programmatic control        npm install @xelvyn/sdk
  @xelvyn/skills     Pre-built agent capabilities (9 skills)        xelvyn skill install <name>
$ xelvyn quickstart
  [1] npm install -g @xelvyn/cli
  [2] xelvyn login
  [3] xelvyn init my-agent --template yield --network base
  [4] xelvyn skill install yield-rebalancer --ai openai
  [5] xelvyn deploy --x402 --xmtp
  [6] xelvyn status my-agent --live
  Agent deployed. Autonomous execution active.
$ xelvyn stack
  COMPONENT          VALUE
  Network            Base (Chain ID: 8453)
  Currency           USDC
  Payments           x402 Protocol (HTTP 402)
  Messaging          XMTP v3 (MLS encryption)
  Compute            Isolated VPS per agent
  Runtime            Node.js 20+
  Language           TypeScript
  AI (opt-in)        OpenAI GPT-4o / Anthropic Claude
$ xelvyn links
  Platform           https://xelvyn.xyz
  Documentation      https://xelvyn.xyz/docs
  Skills Library     https://xelvyn.xyz/skills
  npm CLI            https://www.npmjs.com/package/@xelvyn/cli
  npm SDK            https://www.npmjs.com/package/@xelvyn/sdk
  npm Skills         https://www.npmjs.com/package/@xelvyn/skills
  X / Twitter        https://x.com/Xelvyn_
$ xelvyn license
  MIT
