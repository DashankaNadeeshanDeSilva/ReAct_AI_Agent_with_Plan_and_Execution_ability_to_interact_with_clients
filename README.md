# ReAct_AI_Agent_with_Plan_and_Execution_ability_to_interact_with_clients
ReAct AI Agent with Plan and Execution ability to handle client services management

The success of an agent in an environment depends on the tools it has access to and the strength of its AI planner.

Tools:

Tools help an agent to both perceive the environment and act upon it. Actions that allow an agent to perceive the environment are read-only actions, whereas actions that allow an agent to act upon the environment are write actions.


Some queries might be out of the scope of the agent. The intent classifier before agent planning should be able to classify requests as IRRELEVANT so that the agent can politely reject those instead of wasting FLOPs coming up with impossible solutions. (.e.g. asking irrelevent question like how is the weather now from a customer support ai agent)
