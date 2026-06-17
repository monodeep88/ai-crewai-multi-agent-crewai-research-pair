# Generation Notes

Mode: ai

Model: groq / llama-3.1-8b-instant

Fallback reason: OpenAI limit reached. Automatically switched to Groq.

Architecture: CrewAI Research Operations Crew

Template path: templates/crewai-multi-agent/crewai-research-operations-crew

Short description:

A multi-agent system for research collaboration and knowledge sharing

Architecture notes:

- Use a graph database to store and link research knowledge
- Implement a microservices architecture for scalability and flexibility
- Use API-based communication between components

Project planner agent workflow:

- Architecture Agent: Define app boundaries, data flow, runtime stack, and integration points. Outputs: Use a graph database to store and link research knowledge; Implement a microservices architecture for scalability and flexibility; Use API-based communication between components
- Backend Agent: Design FastAPI modules, service contracts, validation, and error handling. Outputs: Research Hub API: API for interacting with the Research Hub; Knowledge Graph API: API for interacting with the Knowledge Graph; Collaboration Module API: API for interacting with the Collaboration Module
- Frontend Agent: Design React screens, state flow, controls, and user feedback states. Outputs: Research Dashboard: Dashboard for viewing and managing research projects; Knowledge Graph Explorer: Tool for exploring and linking research knowledge; Collaboration Workspace: Workspace for team collaboration and communication
- Database Agent: Design persistence models, sample data, indexes, and audit records. Outputs: Run history; Source document metadata; Generated workflow audit records
- Testing Agent: Define contract tests, smoke tests, and generated project validation. Outputs: {'types': ['Unit testing', 'Integration testing', 'End-to-end testing'], 'tools': ['Pytest', 'Jest', 'Cypress']}
- DevOps Agent: Define environment variables, Docker workflow, and repository packaging. Outputs: Docker-ready project; Environment sample file; GitHub repository upload
- Reviewer Agent: Review the generated plan for completeness, security, and portfolio quality. Outputs: Research Project Setup: Create a new research project and set up the Research Hub; Knowledge Graph Population: Populate the Knowledge Graph with relevant research knowledge; Team Collaboration: Facilitate team collaboration and communication using the Collaboration Module
