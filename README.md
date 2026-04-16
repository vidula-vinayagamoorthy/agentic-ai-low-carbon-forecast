🎬Agentic AI Low Carbon Forecast
---
Demonstration of an agentic AI-driven analytics pipeline designed to help a manufacturing company tackle a critical sustainability challenge facing their five UK production facilities. Aim is to build an intelligent forecasting system that learns from 30 days of historical weather and carbon data to predict these low-carbon windows up to 7 days in advance, then identifies which flexible operations can be strategically shifted from high-carbon hours to clean-energy windows. 

✨ Technologies
---
Ascend’s agentic AI orchestration tool, Otto, handles Python, SQL, and API calls, with an underlying Microsoft Foundry integration. Completely prompt-driven: otto plans, executes, validates and iterates. As the agent generates the code, it isn’t included here.

🚀 Features
---
- Autonomous plan, execute, test, self-fix and iterate across when building the data pipelines and dashboards.
- End to end ingestion of multiple data sources, transformation, validation, forecasting, etc
- Prompt-driven executions enabling observability into agent decisions.
- Actionable insights with identification on what needs to happen, so as to reduce environmental impact.

📍 Key Risk Considerations
---
-	Review agent’s execution plan before execution! Ask for this to be built in your prompt.
-	Use prompts to build iteratively, run, test, fix errors, before executing end to end
-	Ensure human-in-the-loop validations: **what is technically correct doesn’t mean analytically correct**! Validate for expected outcome and ensure its explainable to stakeholders!
-	Ask questions to the agent (or ask it to ask you questions!): Check what assumptions the agent has made (which you haven’t provided), what logic has been applied, what code changes were done, etc

🚦 Running the Project
---
You can use the links on the uploaded document. Prompts available to reuse when running Otto.

🎞️ Preview of the output 
--- 
1.	Create Python Read Components for weather and carbon intensity APIs
2.	Build a weather forecast component for the next 7 days
3.	Write SQL transforms to join all five data sources
4.	Build a predictive model for carbon intensity
5.	Calculate optimal scheduling windows for every machine
6.	Test each component individually, then run the full flow end to end
