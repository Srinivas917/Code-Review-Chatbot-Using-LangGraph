Task Instructions:

You have to build a code review assistant chatbot. You can use LangChain and LangGraph frameworks to build the agents. So think of this like a review bot for LeetCode style questions.
So your input to the bot is going to be the question and solution, it must pass through the StateGraph and finally have a response which explains the user giving feedback about their code.

Detailed Instructions:

You will have to build four agents as part of this langgraph framework. Use LangChain to build these agents.
The first agent would take in your input query => which would be the LeetCode question and your solution. The agent would basically identify the language and pass it down to the relevant agent. For simplicity have two agents one for Python and another for C++.
The second agent would be the python/c++ agent, which would take input as the original leetcode question and return an optimized solution (for both time and space complexities).
The third agent would take two inputs (your solution and optimized solution from the second agent) and give feedback on the code, compared with the optimized solution.
After this you need to include “Human in the loop”, where the human will evaluate the feedback from the agent, if the user is happy with the feedback they can exit there.
If the user is not happy and wants further explanation then this must go to the final agent (fourth agent), which would take in the input question, user solution and optimized solution from agent, and give detailed explanation explaining user’s mistakes and how they can improve it as the final response.


Additional Information and References:

For easier understanding, I have laid out how the graph must be for this task, you can use this to build the StateGraph and chatbot. (Please look at page 2).
Docs and videos to refer:
️🔗 LangChain
Learn LangGraph basics
LangGraph Complete Course for Beginners – Complex AI Agents with Python
LangChain for LLM Application Development - DeepLearning.AI


 
