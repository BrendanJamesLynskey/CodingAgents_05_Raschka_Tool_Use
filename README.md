# CodingAgents 05 — Tool Access & Bounded Actions

Companion deck for **Component 3** of Sebastian Raschka's *[Components of a Coding Agent](https://magazine.sebastianraschka.com/p/components-of-a-coding-agent)*. Covers the shift from "model suggests commands in prose" to "agent executes bounded, validated actions": tool-call schemas, the four validation gates, approval modes, the canonical tool taxonomy, schema-design discipline, and the failure modes that show up in real harnesses.

Includes an interactive approval-gate simulator that walks tool calls (including adversarial ones — typo'd names, path escapes, dangerous shell commands) through every stage of validation, and shows the bounded error feedback that lets the model recover.

**Live site:** https://brendanjameslynskey.github.io/CodingAgents_05_Raschka_Tool_Use/

Part of the [Coding Agents Internals sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Coding_Agents). Read [deck 03](https://brendanjameslynskey.github.io/CodingAgents_03_Raschka_Components_Overview/) for the framing and [deck 04](https://brendanjameslynskey.github.io/CodingAgents_04_Raschka_Repo_Context_And_Caching/) for the prompt architecture this builds on.
