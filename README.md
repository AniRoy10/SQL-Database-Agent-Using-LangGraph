In this repo we have created a solution where based on user query LLM can work as a Database agent and fetch the matching data from the DB.

We have used open source llama3-70b-8192 from Groq and LangGraph's agentic framework to build the agent.

Step1: We have created an sqlite3 connection to the Database and Populated the DB with relevant Data 

Step2: we have used SQLDatabaseToolkit from langchain and passed the DB and the LLM as an argument to create an object

Step3: we have created a custom db_query_tool with run_no_throw option for the LLM to interact with the DB

Step4: with the help of prompt engineering and stateflows from LangGraph we have created the AI agent

Step5: we have added the nodes and the edges in order to compile the workflow and visualize it.
