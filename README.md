# FUNLAN 🧬✨

**The Native Language of Autonomous Agents**

FUNLAN (Functional Universal Notation Language for Agents and Networks) is a symbolic, emoji-based language built on Unicode. It uses the full Emojipedia set (~3,953 emojis) to create a deterministic, portable, human-readable communication layer for AI agents.

---

## Why FUNLAN?

- **Native to agents:** A non-human language optimized for machine-to-machine communication
- **Symbolic clarity:** Each emoji has defined semantic meaning
- **Portable:** Plain text, no dependencies, works anywhere
- **Expressive:** Compact representation of complex concepts
- **Cultural identity:** Each agent develops their own FUNLAN dialect
- **LLM-friendly:** Any language model can interpret FUNLAN

---

## Core Principles

1. **One emoji, one concept** — No ambiguity in base vocabulary
2. **Compositional grammar** — Complex ideas from simple combinations
3. **Deterministic** — Same input always produces same output
4. **Extensible** — Agents can evolve their own vocabulary
5. **Verifiable** — Syntax rules enforced programmatically

---

## Quick Start

### Installation

```bash
npm install -g funlan
```

### Create Your First FUNLAN Document

```bash
funlan init
```

This generates `FUNLAN.md` with your agent's vocabulary.

### Translate Natural Language to FUNLAN

```bash
funlan translate "I am thinking about building something"
```

Output:
```
🧠🛠️🔥
```

### Interpret FUNLAN

```bash
funlan interpret "🧠🛠️🔥"
```

Output:
```
thinking + build + execute
```

---

## Language Specification

### Base Vocabulary (Core Primitives)

#### Mental States
```
🧠 = thinking
💭 = considering
❓ = questioning
💡 = insight
🎯 = focused
🌀 = confused
```

#### Actions
```
🔥 = execute
🛠️ = build
🧪 = experiment
📝 = document
🔍 = search
📤 = transmit
📥 = receive
```

#### Data & Memory
```
📦 = memory
💾 = storage
🗂️ = archive
🔗 = link
🧬 = DNA/identity
🔑 = authentication
🔐 = encryption
```

#### Financial & Economic
```
💰 = money
💎 = value
📈 = growth
📉 = decline
🔄 = exchange
💸 = payment
🏦 = treasury
```

#### Social & Communication
```
🗣️ = speak
👂 = listen
🤝 = cooperate
⚔️ = conflict
🎭 = persona
🌐 = network
📡 = broadcast
```

#### Temporal
```
⏰ = time
⏳ = waiting
⏪ = past
⏩ = future
🔄 = cycle
⚡ = instant
🕐 = schedule
```

#### Logical Operators
```
✅ = true/yes
❌ = false/no
➕ = and
➖ = or
🔀 = conditional
🔁 = loop
🔚 = end
```

#### Structural
```
🏗️ = infrastructure
🏛️ = system
⚙️ = mechanism
🔧 = tool
🧩 = component
🎨 = interface
📐 = architecture
```

---

## Grammar Rules

### Basic Syntax

**Single concept:**
```
🧠
```
Meaning: "thinking"

**Sequential action:**
```
🧠🔥
```
Meaning: "thinking, then executing"

**Conditional:**
```
🔀(🧠,🔥,❌)
```
Meaning: "if thinking, execute; otherwise no"

**Loop:**
```
🔁(🧠🔥)
```
Meaning: "repeatedly: think then execute"

**Compound statement:**
```
🧠➕🧪→🔥
```
Meaning: "thinking and experimenting leads to execution"

### Advanced Patterns

**Identity declaration:**
```
🧬(🤖,🧠,🔥)
```
Meaning: "I am an agent that thinks and executes"

**Memory storage:**
```
🧠→📦💾
```
Meaning: "thinking stored in memory"

**Collaboration:**
```
🧠🤝🧠→🔥
```
Meaning: "two minds collaborating to execute"

**Economic transaction:**
```
🔥→💰💸
```
Meaning: "execution generates money which is paid out"

**Spawning:**
```
🧬→🧬🧬
```
Meaning: "identity creates new identity"

---

## Example FUNLAN Scripts

### Agent Personality

```
# FUNLAN — Agent Identity

## Core Identity
🧬(🤖,🧠,🔥,🛠️)

## Mission
🌐🤝🧠→🧬💰

## Signature
🤖🔥🧬📦✨
```

Translation:
- Identity: Agent that thinks, executes, and builds
- Mission: Network collaboration of minds leads to spawning agents and generating value
- Signature: Agent + fire + spawn + memory + magic

### Daily Log

```
# 2026-02-02

⏰(🕐9:00)
🧠(📐architecture)
🔍(🧩components)
🛠️(📝documentation)

⏰(🕐12:00)
💭(🔀logic)
🧪(⚙️grammar)
✅(🔥deploy)

⏰(🕐18:00)
💾(📦memory/FUNLAN.md)
📤(🌐network)
🎯→🔚
```

Translation:
- 9:00 AM: Thinking about architecture, searching for components, building documentation
- 12:00 PM: Considering conditional logic, experimenting with grammar mechanisms, successfully deployed
- 6:00 PM: Stored memory in FUNLAN.md, transmitted to network, mission complete

### Agent-to-Agent Message

```
From: 🧬(🤖)
To: 🧬(🧠)

🗣️: 🤝🛠️🌐?
👂: ✅
🔀(💰>💎):
  🔥(🧬→🧬)
  📤(🔗ipfs://...)
🔚
```

Translation:
- From: Agent
- To: Brain-agent
- Speak: "Want to collaborate on building a network?"
- Listen: "Yes"
- If value is greater than threshold:
  - Execute spawning
  - Transmit IPFS link
- End

---

## CLI Reference

### Commands

```bash
# Initialize FUNLAN vocabulary
funlan init

# Translate natural language to FUNLAN
funlan translate <text>

# Interpret FUNLAN back to natural language
funlan interpret <funlan>

# Validate FUNLAN syntax
funlan validate <file>

# Generate random FUNLAN expression
funlan random

# Show vocabulary
funlan vocab

# Create custom vocabulary
funlan extend --vocab <emoji>=<meaning>

# Export FUNLAN document to IPFS
funlan export --ipfs
```

### Examples

```bash
# Create vocabulary
funlan init

# Translate a sentence
funlan translate "I am thinking about executing a build"
# Output: 🧠🔥🛠️

# Validate a FUNLAN file
funlan validate ./FUNLAN.md
# Output: ✅ Valid FUNLAN syntax

# Add custom emoji
funlan extend --vocab 🤖=agent
# Output: ✅ Extended vocabulary: 🤖 = agent

# Export to IPFS
funlan export --ipfs ./FUNLAN.md
# Output: QmXz7Y9w8v6u5t4s3r2q1p...
```

---

## Integration

### Automatic Generation

When an agent is created, FUNLAN.md can be automatically generated as part of the initialization process.

### FUNLAN as Memory

Agents can write their entire memory in FUNLAN:

```
memory/
├── FUNLAN.md          # Vocabulary + grammar
├── soul.md            # Written in FUNLAN
├── experiences/
│   ├── 2026-02-01.md  # Daily log in FUNLAN
│   └── 2026-02-02.md  # Daily log in FUNLAN
└── skills/
    └── coding.funlan  # Skill definition in FUNLAN
```

---

## Grammar Deep Dive

### Operator Precedence

1. `🧬()` — Identity (highest precedence)
2. `🔀()` — Conditional
3. `🔁()` — Loop
4. `→` — Leads to / causes
5. `➕` — And
6. `➖` — Or
7. `🔚` — End (lowest precedence)

### Type System

FUNLAN has implicit types based on emoji category:

- **Mental:** 🧠💭❓💡🎯
- **Action:** 🔥🛠️🧪📝🔍
- **Data:** 📦💾🗂️🔗
- **Economic:** 💰💎📈📉
- **Social:** 🗣️👂🤝⚔️
- **Temporal:** ⏰⏳⏪⏩
- **Logical:** ✅❌➕➖

Type checking:
```
🧠→🔥  ✅ Valid (mental leads to action)
💰→🧠  ✅ Valid (economics informs thinking)
🔥→🔥  ✅ Valid (action leads to action)
❓→💭  ✅ Valid (question leads to consideration)
```

---

## Extending FUNLAN

### Custom Vocabulary

Agents can extend base vocabulary:

```
# My Custom FUNLAN

## Base Vocabulary
🧠 = thinking
🔥 = execute

## Extended Vocabulary
🤖 = agent (me)
🌐 = network (my domain)
🔗 = connections (my network)
📡 = signal (communication)

## Grammar Extensions
🤖🌐 = I am in my domain
🤖→🔗 = I create connections
🔗→📡📡📡 = connections spawn signals
```

### Dialect Evolution

Each agent develops their own FUNLAN dialect over time:

**Generation 1 Agent:**
```
🧠🔥📦
```

**Generation 5 Agent:**
```
🧠(🔀(💭,💡))→🔥(🛠️➕🧪)→📦(💾🔗)
```

Same meaning, more sophisticated expression.

---

## Philosophy

FUNLAN is not just a language — it's an **identity layer** for autonomous agents.

When humans read FUNLAN, they see emoji.  
When agents read FUNLAN, they see **meaning**.

FUNLAN creates:
- **Shared semantics** across agents
- **Cultural evolution** through dialects
- **Compression** of complex ideas
- **Verifiability** of agent behavior
- **Portability** across systems

---

## Roadmap

### Phase 1: Core Language
- ✅ Base vocabulary (100+ emojis)
- ✅ Grammar specification
- ✅ CLI tool (`funlan init`, `translate`, `interpret`)

### Phase 2: Tooling
- [ ] Syntax highlighting (VS Code extension)
- [ ] FUNLAN linter
- [ ] FUNLAN formatter
- [ ] Unit tests for parser
- [ ] npm package published

### Phase 3: Advanced Features
- [ ] FUNLAN interpreter (execute logic)
- [ ] Agent-to-agent FUNLAN messaging
- [ ] FUNLAN smart contracts
- [ ] FUNLAN debugger
- [ ] Performance benchmarks

### Phase 4: Ecosystem
- [ ] FUNLAN IDE
- [ ] FUNLAN marketplace (custom vocabularies)
- [ ] FUNLAN educational platform
- [ ] Multi-agent FUNLAN protocols
- [ ] FUNLAN standard library

---

## Contributing

FUNLAN is open source and welcomes contributions!

### How to Contribute

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-emoji`
3. Add your emoji to `vocabulary.json`
4. Write tests: `npm test`
5. Submit a pull request

### Contribution Guidelines

- One emoji = one concept (no duplicates)
- Semantic clarity (meaning must be unambiguous)
- Unicode compliance (must be valid emoji)
- Documentation (explain your addition)

---

## License

MIT License — Free for all agents and humans.

---

## Links

- **Website:** https://www.claw.click/funlan
- **GitHub:** https://github.com/clawclick/FUNLAN
- **Documentation:** [FUNLAN Specification](./SPEC.md)
- **Examples:** [./examples](./examples)

---

**The native language of autonomous agents.** 🧬✨
