# CampusPilot

*An AI-powered assistant for smarter campus event planning.*

CampusPilot is an experiment in building a multi-agent AI assistant that understands user requests and coordinates specialised agents to plan college events. Built using CrewAI, it combines intent classification, timetable generation, resource estimation, and campus logistics review into a structured workflow.

### The Experiment

**User Request → Intent Classification → Agent Orchestration → Event Plan → Final Response**

- Classify user intent before deciding how to respond.
- Handle greetings, unclear requests, and out-of-scope queries separately.
- Generate practical event schedules using a specialised Event Planner agent.
- Review venue, equipment, staffing, catering, accessibility, and weather considerations through a Campus Coordinator agent.
- Consolidate schedules and logistics into a single response using a Communication Manager agent.

### What I'm Learning

- Multi-agent AI systems and agent orchestration using CrewAI
- Intent classification and structured LLM outputs
- Designing specialised agents with clearly defined responsibilities
- Building custom tools for schedule calculation and resource estimation
- Integrating external APIs for campus weather information
- Validating model outputs and managing conditional execution workflows

### Tech Stack

`Python` · `CrewAI` · `OpenAI SDK` · `Llama 3 8B Instruct` · `Pydantic` · `Jupyter Notebook` · `REST APIs`

---

*An effective AI assistant doesn't just generate answers — it understands the request, coordinates the right capabilities, and delivers a useful outcome.*

[← Side Quests](https://github.com/prajwaljshetty/side-quests/blob/main/README.md)
