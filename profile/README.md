# Hopx — The cloud for AI Agents  

**Hopx** provides ultra-fast, fully isolated **Linux microVMs** for AI agents, developers, and autonomous systems.  
Spin up secure sandboxes in milliseconds. Run untrusted code safely, at any scale.  

> The new Cloud 2.0 — built for the agentic era.

---

## 🚀 What You Can Build with Hopx

- **AI Agents** that execute real code, securely and continuously  
- **Multi-Agent Systems** where each agent runs in its own isolated VM  
- **Workflows & Backends** that scale instantly, without containers or DevOps overhead  
- **Ephemeral Environments** for testing, automation, or code execution  

---

## 🛠️ SDKs Available

Hopx SDKs let you create, run, and manage sandboxes programmatically — with just a few lines of code.

| Language | Package | Docs |
|-----------|----------|------|
| Python | `pip install hopx-ai` | [→ Python Docs](https://pypi.org/project/hopx-ai/) |
| JavaScript / TypeScript | `npm install hopx-ai/sdk` | [→ JS Docs](https://www.npmjs.com/package/@hopx-ai/sdk) |

---

## ⚙️ Example

### Python
```python
from hopx_ai import Sandbox

sandbox = Sandbox.create(template="python:3.11")
result = sandbox.run("print('Hello from Hopx!')")
print(result.output)

### Javascript
```javascript
import { Sandbox } from "hopx-ai";

const sandbox = await Sandbox.create({ template: "node:20" });
const result = await sandbox.run(`console.log("Hello from Hopx!")`);
console.log(result.output);
```

## 🔒 Why Hopx

- **<100 ms startup time**  
- **Full Linux isolation** via Firecracker microVMs  
- **Unlimited runtime**  
- **Regional latency routing** (US / EU / Asia)  
- **Pay-as-you-go credits**

---

## 🌍 Links

- [Website](https://hopx.ai)  
- [Documentation](https://docs.hopx.dev)  
- [Twitter / X](https://x.com/bunnyshell_eaas)  

---

Hopx is building the **runtime layer for the next cloud** — a cloud where *agents*, not humans, deploy code.  
Help us shape the future of AI infrastructure.

> Try it now — [Get $200 free credits →](https://hopx.ai)
