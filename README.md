# Multi-AI-Agents-Models using CrewAI

This repository features 5 advanced projects showcasing the integration of AI agents with CrewAI, demonstrating expertise in AI-driven task automation, large language models (LLMs), and software engineering for operational efficiency. Each project addresses a unique business or analytical need, leveraging CrewAI’s structured agents, tasks, and flows in dynamic configurations.

## Folder Structure

```
1_project_management.ipynb      # Notebook: Project Management Crew
2_progress_report.ipynb         # Notebook: Progress Report Crew
3_Sales_Pipeline.ipynb          # Notebook: Sales Pipeline Crew
4_Support_Data_Analysis.ipynb   # Notebook: Support Data Analysis Crew
5_Scaled_Content_Creation.ipynb # Notebook: Scaled Content Creation Crew
config/                          # YAML configuration files for agents and tasks
helper.py                        # Helper functions
requirements.txt                 # Python dependencies
venv/                            # Virtual environment for project dependencies
support_tickets_data.csv         # Data for support data analysis crew
sales_pipeline_flow.html         # Visualization for the sales pipeline flow
training.pkl                     # Pickled training data for model improvements
trello.png                       # Reference image
```

## Project Overviews

Each project is built within its own Jupyter notebook and showcases the use of agents, tasks, crews, and flows to address specific business problems or automation needs.

### 1. Project Management Crew (`1_project_management.ipynb`)

The Project Management Crew automates and streamlines project planning, estimation, and resource allocation using Sequential and Hierarchical flows:
- **Sequential Process**: Ensures a structured task progression.
- **Hierarchical Process**: Introduces a `manager_llm` or `manager_agent` to delegate tasks based on a managerial hierarchy.
- **Core Skills Demonstrated**: Project planning, resource management, and coordination using LLMs for task execution.

### 2. Progress Report Crew (`2_progress_report.ipynb`)

The Progress Report Crew is designed to generate automated progress reports based on project and task metrics.
- **Sequential Process**: Ensures ordered task execution for structured report generation.
- **Training and Testing Workflow**: Trains and tests agents to produce accurate and relevant metrics.
- **Core Skills Demonstrated**: Automated report generation, metric tracking, and LLM-driven data processing.

### 3. Sales Pipeline Crew (`3_Sales_Pipeline.ipynb`)

Automates lead qualification, engagement tracking, and conversion metrics within a structured sales pipeline.
- **Hierarchical Flow**: Manages tasks based on lead stages, coordinating agents for qualification, scoring, and engagement.
- **Visualization**: Includes an HTML-rendered flow chart to depict sales stages and agent actions.
- **Core Skills Demonstrated**: Sales analytics, lead management, multi-stage processing with LLMs.

### 4. Support Data Analysis Crew (`4_Support_Data_Analysis.ipynb`)

Processes support tickets to provide insights into user issues and help refine support strategies.
- **Sequential Process**: Ensures efficient ticket processing.
- **Data Analysis**: Analyzes support data (`support_tickets_data.csv`) for actionable insights.
- **Core Skills Demonstrated**: Data analytics, sentiment analysis, automated customer support processing with LLMs.

### 5. Scaled Content Creation Crew (`5_Scaled_Content_Creation.ipynb`)

Automates scalable content creation using multiple language models for enhanced throughput.
- **Hierarchical and Sequential Flows**: Applies both workflows to produce content efficiently and maintain consistency.
- **Multi-Model Integration**: Combines outputs from various LLMs for a robust content pipeline.
- **Core Skills Demonstrated**: Scalable LLM-based content generation, task coordination, and hierarchical management for content quality.

## Processes Used

1. **Sequential Process**: Executes tasks in a strict order, ensuring each task completes before the next starts.
2. **Hierarchical Process**: Organizes tasks within a managerial hierarchy, using either `manager_llm` or `manager_agent` to oversee tasks.
3. **Consensual Process (Planned)**: Designed for collaborative decision-making between agents. This process will be implemented in future versions.

## Training and Testing

The **training crew** allows for programmatic improvements in agent performance:
1. Define training iterations.
2. Set input parameters for training.
3. Run with error handling to ensure smooth operation.

The **testing crew** runs iterative tests to evaluate performance, showcasing agents' adaptability and the reliability of CrewAI configurations for robust task automation.

## Requirements

Install dependencies from `requirements.txt`:
```bash
pip install -r requirements.txt
```

## Configuration Files

- The `config/` folder contains YAML files (e.g., `agents.yaml`, `tasks.yaml`) to define agent and task specifications for each crew. Modify these files to adapt the crew configuration.

## Running the Project

1. Activate the virtual environment:
   ```bash
   source venv/bin/activate
   ```
2. Open the desired notebook and run all cells to execute the crew configurations and workflows.

## Conclusion

These projects highlight my expertise in integrating and managing LLMs within complex workflows, leveraging CrewAI to automate, scale, and optimize task management. From project management to data analysis and content creation, each crew demonstrates innovative use of agent-based systems to deliver efficient and scalable solutions.
