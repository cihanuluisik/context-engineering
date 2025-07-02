Before we talk about Model Context Protocol (MCP), here's how typical tool calling with LLMs work:

1. Prompt goes to the LLM.
2. LLM decides which tool to use.
3. Custom glue code builds the function call.
4. Backend runs the tool.

Everything is hand-wired, which is great for demos but painful at scale.

Enter MCP 🚀

↳ A lightweight protocol that standardizes how tools are described, discovered, and executed.

↳ No glue code: Drop in an MCP server; the client + LLM handle the rest.

↳ Self-describing: Schemas are auto-published, so agents know the inputs/outputs.

↳ Permissioned: Tools can require explicit approval before they run.

↳ Decoupled: Implementation lives on the server; consumers just send a spec.

Result: you focus on building tools once, not re-integrating them for every agent.

How They Fit Together 🤝

Function Calling lets the LLM say what it wants, but you still wire up and run the code. MCP picks up from that intent: it finds the right tool, feeds it the inputs, runs it on the server, and returns the result.

In one line—Function Calling captures intent; MCP handles everything else.

For example, an agent might say, “I need to search the web,” using function calling.

That request can be routed through MCP to select from available web search tools, invoke the correct one, and return the result.

If you want to understand this better with code, I have linked my article in the comments.

![MCP vs Function Calling](MCP%20vs%20Function%20calling.png) 