**Step 1:**
Checking Input using Input Moderation.
Generating a sample customer comment.
Using OpenAI's Moderation API to check if it's inappropriate.

**Preventing Prompt Injection:**
Generating a prompt injection for electronic products.
Implementing a mechanism to prevent prompt injection.

**Step 2:**
Classifying Service Requests based on the user's input message.

**Step 3:**
Answering User Questions using Chain of Thought Reasoning to provide detailed responses.

**Step 4: **
Checking Outputs, using self-evaluation to verify factual accuracy.

**Step 5: **
handles Evaluation Part 1 by comparing responses to ideal answers across test cases.

**Step 6: **
covers Evaluation Part 2:
Evaluating answers using a rubric based on extracted product info.

Comparing answers to ideal/expert human responses.
Checking for normal vs abnormal assistant answers.
