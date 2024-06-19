# AI Agents using CrewAI and Gemini
This repository contains a project that leverages AI agents using CrewAI and Google Gemini to research and write about the latest trends in AI technology, specifically focusing on healthcare. 

## Project Overview
The project consists of two main AI agents:

- **News Researcher:** A senior researcher agent responsible for uncovering groundbreaking technologies in healthcare, with a focus on identifying the pros and cons and overall narrative of AI trends in healthcare.
- **News Writer:** A writer agent that composes engaging and insightful articles based on the research conducted by the News Researcher, simplifying complex topics for a broader audience.

## Key Components
**Research Task:** Conducts comprehensive research to identify the next big trend in AI for healthcare. The output is a detailed report on the latest AI trends.
**Write Task:** Composes an insightful and engaging article based on the research findings, focusing on the latest trends and their impact on the healthcare industry.

## Workflow
1. **Initialize Agents:** Load environment variables and initialize AI agents with specified roles and goals.
2. **Define Tasks:** Create research and writing tasks with clear descriptions and expected outputs.
3. **Kickoff:** Start the task execution process with the specified topic (AI in healthcare).

## Dependencies
**crewAI:** A library for creating and managing AI agents.
**langchain_google_genai:** Interface for Google Generative AI.
**SerperDevTool:** Tool for internet searching capabilities.

##Environment Variables
Ensure to set up the following environment variables:

**GOOGLE_API_KEY:** Your Google API key for the Generative AI.
**SERPER_API_KEY:** Your Serper API key for internet searching capabilities.

$$ Output
The expected output includes:
- A detailed research report on AI trends in healthcare.
- An engaging and insightful article based on the research.
  
## License
This project is licensed under the MIT License. See the LICENSE file for details.
