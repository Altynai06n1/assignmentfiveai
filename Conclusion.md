1. Which layer changed your results the most?
Layer 1 had the biggest impact. Correct answers increased from 16 to 18, while unanswered questions dropped from 4 to 0.
However, wrong answers increased from 4 to 6. Layer 2 made no changes.
Layer 3 reduced wrong answers to 4 but increased unanswered questions to 2. So, only Layer 1 improved the number of correct answers.

2. One failure the full harness did not fix
Q08 stayed wrong in every version. The model chose the first region instead of the last when looking for the lowest average monthly wage.
The answer was found in the tool output, so the grounding check accepted it. A useful fix would be an extra check to make sure the model selects the last region for "lowest" questions.

3. Workflow or agent for the monthly ranking?
I would choose the fixed workflow. It answered 13 out of 15 questions correctly, with no wrong answers.
It used 15 model calls, 3,852 tokens, and 16.1 seconds. The bare agent got only 9 correct and used 26 calls, 19,835 tokens, and 65 seconds.
The workflow is better for regular monthly rankings. The agent is more useful for complex questions that need multiple steps or calculations.
