# ADK Multi-Agent Debate Examples

This repo contains examples of using Google's Agent Development Kit (ADK) to create autonomous multi-agent debates and interactions. The goal is to showcase how ADK can orchestrate multiple AI agents to perform a structured task, like debating a specific topic, without direct human intervention during the process.

## What is ADK?

The Agent Development Kit (ADK) is a framework designed to help developers build, orchestrate, and manage applications powered by multiple AI agents. It provides tools for defining agent roles, managing conversation state, and controlling the flow of interaction between agents and potentially humans or other tools.

Think of it as a way to build more complex AI systems where different specialized agents collaborate or compete to achieve a goal.

## Examples Included

* **Hot Dog vs. Sandwich Debate:** The classic, pointless, yet surprisingly engaging debate about whether a hot dog qualifies as a sandwich. This demonstrates basic agent roles (pro, con, moderator), turn-based interaction, and context management.
    * See the [Blog Post Version](hotdog.md) for a narrative walkthrough.
* *(Add other examples here as you create them, e.g., Vim vs. Emacs, Epstein Death Debate Analysis)*

## Running the Examples

*(This section will need specifics based on your actual code structure, but here's a general template)*

1.  **Prerequisites:**
    * Python environment (e.g., 3.10+)
    * Google Cloud Project with necessary APIs enabled (e.g., Vertex AI)
    * Authentication configured (e.g., `gcloud auth application-default login`)
    * ADK library installed (`pip install google-adk -U`)
    * *(Any other specific libraries)*
2.  **Setup:**
    * Clone this repository: `git clone <your-repo-url>`
    * Navigate to the repository directory: `cd <your-repo-name>`
    * *(Optional: Set up a virtual environment)*
    * Install dependencies: `pip install -r requirements.txt` *(if you create one)*
3.  **Execution:**
    * *(Provide specific commands to run each debate example, e.g., `python run_hotdog_debate.py`)*

*Note: These examples rely on LLMs (like Gemini). Running them will incur costs associated with API calls.*

## Key ADK Concepts Demonstrated

* **Agent Definition:** Defining distinct roles, instructions, and potential tools for each agent (See [ADK Quickstart](https://google.github.io/adk-docs/get-started/quickstart/)).
* **Orchestration:** Managing the turn-based flow and passing context between agents (See [ADK Samples](https://github.com/google/adk-samples) for patterns).
* **State Management:** Implicitly handled by ADK to maintain conversation history for context.

## Resources

* **ADK Documentation:** <https://google.github.io/adk-docs/>
* **ADK API Reference:** <https://google.github.io/adk-docs/api-reference/>
* **ADK Samples Repository:** <https://github.com/google/adk-samples>
* **ADK Hackathon (Ends Soon!):** <https://googlecloudmultiagents.devpost.com/>

## Contributing

Try out ADK! Feel free to fork, or use this as content, or recommend improvements! I'm working on adding personalities that I provide as vars for each debate agent as well! The agents no longer are forced into a stance, but determine their own. Contribute if you have ideas!

