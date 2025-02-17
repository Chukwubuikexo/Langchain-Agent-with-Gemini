# LangGraph and LangChain Academy: Project 1 - Agent with Memory

This repository contains a Jupyter Notebook (`Agent-with-memory.ipynb`) that demonstrates the implementation of an agent with memory using **LangGraph** and **LangChain**. The project focuses on creating a conversational agent capable of performing arithmetic operations while maintaining context across interactions.

## Overview

The notebook showcases the following key concepts:

1. **LangGraph Integration**: The agent is built using LangGraph, a library for creating stateful, graph-based conversational agents.
2. **Memory Management**: The agent is equipped with memory, allowing it to retain context across multiple interactions.
3. **Arithmetic Operations**: The agent can perform basic arithmetic operations (addition, multiplication, and division) based on user input.
4. **Tool Integration**: The agent uses predefined tools (`add`, `multiply`, `divide`) to execute arithmetic tasks.

## Features

- **Stateful Conversations**: The agent maintains context across multiple user inputs, enabling more natural and coherent interactions.
- **Tool-Based Execution**: The agent uses predefined tools to perform arithmetic operations, demonstrating how to integrate external functions into a conversational agent.
- **Memory Checkpointing**: The agent's memory is saved and restored using LangGraph's `MemorySaver`, allowing for persistent context across sessions.

## Requirements

To run this notebook, you need the following dependencies:

- Python 3.10
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`):
  - `langgraph`
  - `langchain`
  - `google-generativeai`
  - `IPython`.......

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Chukwubuikexo/Langchain-Agent-with-Gemini.git
   cd Langchain-Agent-with-Gemini/Project-1
   ```

2. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook Agent-with-memory.ipynb
   ```

3. **Follow the Notebook**:
   - The notebook is divided into sections that demonstrate the setup, execution, and memory management of the agent.
   - You can interact with the agent by providing arithmetic tasks and observing how it maintains context across interactions.


## Memory Management

The agent uses LangGraph's `MemorySaver` to store and retrieve conversation states. This allows the agent to remember previous interactions and continue conversations seamlessly.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **LangGraph**: For providing the framework to build stateful conversational agents.
- **LangChain**: For enabling the integration of tools and memory into the agent.
- **Google Generative AI**: For providing the underlying language model used in this project.

---

For any questions or issues, please contact [Chukwubuikexo](https://x.com/Chukwubuikexo).
