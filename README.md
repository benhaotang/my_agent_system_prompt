This is a repo that keeps some of the system prompts for the agents that I built and used in select AI clients

- Msty Studio (current in beta)
    - [General Research agent with Chain of draft and Tool use](./msty_general_research.md)
        - Toolsets: 
            - [openai-websearch-mcp](https://github.com/tiovikram/openai-websearch-mcp)
            - official fetch or [fetch-mcp](https://github.com/egoist/fetch-mcp)
            - Memory
            - [code-sandbox](https://github.com/Automata-Labs-team/code-sandbox-mcp)
        - Inspiration:
            - Official Claude documentation: [https://docs.anthropic.com/en/release-notes/system-prompts](https://docs.anthropic.com/en/release-notes/system-prompts)
            - Chain of Draft from [arXiv:2502.18600](https://arxiv.org/abs/2502.18600)
        - Use case:
            - Knowledge QA
            - Data analyzing
            - News
        - Recommended llms:
            - Claude sonnet 3.5/3.7 for the best agenetic quality
            - Gemini 2.0 for long context
    - [AI Pre-research agent](./msty_ai_preresearch.md)
        - Toolsets:
            - My [semantic-scholar mcp server](https://github.com/benhaotang/mcp-semantic-scholar-server)
        - Use case:
            - Find papers on a topic
            - Find new research topics
        - Recommended llms:
            - Any models that have a wide range of knowledge and hallucinate less.

License: MIT