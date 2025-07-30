# 🤖 awesome-claude-code-subagents

A curated list of Claude sub-agent designs, helper prompts, and modular tools that make it easier to build multi-step AI workflows — especially for coding, reasoning, and structured task delegation.

This collection focuses on **Claude-based sub-agents**: small, focused units that help orchestrate or handle specific steps within a larger AI agent system.

---

## 🧩 What Are Sub-Agents?

Sub-agents (or helper agents) are modular AI behaviors that handle isolated responsibilities — like:

- 🔍 Searching for files
- 🛠 Refactoring code blocks
- 🧠 Suggesting architecture changes
- 📄 Generating documentation
- 📦 Running tests or validations

In Claude-based systems, sub-agents help break down complex coding workflows into reliable, explainable, and reusable steps.

---

## 📦 What's Inside?

- 🧠 **Claude Prompt Patterns for Sub-Agents**  
  Examples of how to structure prompts for focused responsibilities.

- ⚙️ **Sub-Agent Templates**  
  Standard input/output shapes for common tasks like refactoring, summarizing, or evaluating code.

- 🛠 **Real-World Use Cases**  
  Modular building blocks for larger Claude agents (e.g., supervisors, tool-using agents, CI assistants).

- 🌐 **Related Projects**  
  Pointers to open source frameworks using sub-agent strategies.

---

## 🧪 Example Sub-Agent Patterns

- `codeReviewerAgent(prompt, diff) → suggestions[]`
- `functionExplainerAgent(code) → explanation`
- `fileRouterAgent(filePaths[], goal) → relevantFiles[]`
- `testWriterAgent(fnCode) → testCode`

Each sub-agent focuses on one responsibility, and can be composed into more complex Claude agents.

---

## 🤝 Contribute

Pull requests and issue suggestions welcome!  
If you're building Claude-based agents or helper functions, feel free to share your patterns here.

---

## 📚 Related

- [VoltAgent](https://github.com/voltagent/voltagent) – Open-source TypeScript AI agent framework with Claude support

---

## 📝 License

MIT