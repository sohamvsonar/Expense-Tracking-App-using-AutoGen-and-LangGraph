# Expense Tracking App using AutoGen and LangGraph

This project demonstrates the use of AutoGen agents and LangGraph/LangChain frameworks to simulate a virtual team for the development of an Expense Tracking Application. Each agent in the system is designed to fulfill a specific role within the software development lifecycle, showcasing a modular and automated approach to application development.

## Project Overview

The application models a collaborative team environment where agents handle tasks ranging from requirements engineering to implementation, testing, and documentation. Each agent is powered by OpenAI's GPT models and coordinated using AutoGen.

### Key Features
- **Multi-Agent Collaboration**: Simulates various roles such as Project Manager, Requirement Engineer, System Engineer, and more.
- **Effort Estimation**: Provides a detailed breakdown of effort required for tasks.
- **Extensible Design**: Modular agent definitions for scalability and flexibility.
- **Automated Documentation**: Generates technical documents and user guides.

## Agents and Their Roles

| Agent                     | Responsibility                                         |
|---------------------------|-------------------------------------------------------|
| Customer Proxy Agent      | Interfaces with customers to gather requirements.     |
| Project Manager Agent     | Oversees the project, compiles durations, and tracks progress. |
| Requirement Engineer Agent| Gathers, analyzes, and formalizes application requirements. |
| System Engineer Agent     | Designs system architecture and prepares technical blueprints. |
| Software Engineer Agent   | Implements the features and writes code for the application. |
| Test Engineer Agent       | Creates and executes test cases to ensure quality.    |
| Documentation Engineer Agent| Prepares user guides and technical documents.       |

## Prerequisites

- Python 3.8+
- Required Python packages:
  - `autogen`
  - `langchain`
  - `openai`
  - `pyautogen`

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/sohamvsonar/Expense-Tracking-App-using-AutoGen-and-LangGraph.git
   ```

2. Install dependencies

3. Set up your OpenAI API key by creating a configuration file (`OAI_CONFIG.json`) with the following format:
   ```json
   [
    {
        "model": "gpt-4o",
        "api_key": "your open AI key",
        "tags": ["gpt-4o", "tool"]
    }
   ]
   ```

## Running the Project

To run the project, execute the notebook file:
```bash
jupyter notebook Expense_Tracking_App_using_Autogens_Langgraph.ipynb
```

The notebook guides you through the process of defining agents, running simulations, and generating reports.

## Structure

- **Expense_Tracking_App_using_Autogens_Langgraph.ipynb**: Main notebook for setting up and running the project.
- **OAI_CONFIG.json**: Configuration file for OpenAI API.

## Features in Action

1. **Automated Requirement Gathering**: The Requirement Engineer Agent interacts with the customer proxy to document user needs.
2. **System Design and Implementation**: The System and Software Engineer Agents collaborate to design and build the application.
3. **Quality Assurance**: The Test Engineer Agent ensures robust functionality through test case creation and execution.
4. **Documentation**: The Documentation Engineer Agent produces user manuals and guides for the application.

## Future Enhancements

- Integrating more complex effort estimation models.
- Adding support for multiple project types.
- Expanding agent functionality for advanced collaboration scenarios.

## Acknowledgements

Special thanks to OpenAI, AutoGen, and LangGraph/LangChain communities for their incredible tools and support.

---
Feel free to reach out with any questions or feedback. Contributions are welcome!

