# Generative AI and Agentic Programming Techniques

## 1. Chain of Thought (CoT)
This helps the AI think step by step before giving an answer. It's like showing your work in math class.

**Prompt:** "If John has 3 apples and buys 2 more, how many does he have?"  
**With CoT:** "John has 3 apples. He buys 2 more. So, 3 + 2 = 5 apples."

## 2. In-Context Learning (ICL)
You give the AI examples in the prompt so it learns how to respond. It learns from the pattern you show.

**Prompt:** "Translate to French:  
1. Hello → Bonjour  
2. Thank you → Merci  
3. Good night →"  
**AI completes:** "Bonne nuit"

## 3. X-shot Learning (Zero-shot, One-shot, Few-shot)
This is about how many examples you give the AI. Zero-shot means no examples, one-shot means one, and few-shot means a few.

**Example (Few-shot):**  
**Prompt:** "Q: What is the capital of France?  
A: Paris  
Q: What is the capital of Japan?  
A: Tokyo  
Q: What is the capital of Italy?  
A: Rome"

## 4. ReAct (Reasoning + Acting)
The AI reasons about a problem and then takes an action, like calling a tool or searching. It's useful for agents that need to think and do.

**Prompt:** "What's the weather in Paris?"  
**AI:** "I need to look it up. [Searches] The weather in Paris is sunny and 22°C."

## 5. Self-Ask with Search
The AI breaks a question into smaller ones and answers them using search. It helps with complex questions.

**Prompt:** "Who is the president of the country with the largest population?"  
**AI thinks:** "Which country has the largest population? → China. Who is the president of China? → Xi Jinping."

## 6. Tool-Augmented Prompting
The AI uses tools like calculators, search engines, or APIs to help answer. It's like giving the AI a toolbox.

**Prompt:** "What is 12345 × 6789?"  
**AI:** "Let me use the calculator tool. The answer is 83,817,105."

## 7. Function Calling Prompts
The AI is told to call a specific function when needed. It's useful for structured tasks like booking or calculations.

**Prompt:** "Book a flight from New York to London on June 10."  
**AI:** Calls bookFlight(origin="New York", destination="London", date="June 10")

## 8. Role-based Prompting
You tell the AI to act like a specific role, like a teacher or a doctor. This helps it respond in the right tone and style.

**Prompt:** "You are a friendly math tutor. Explain what a fraction is."  
**AI:** "Sure! A fraction shows a part of a whole. Like 1/2 means one out of two equal parts."

## 9. Multi-turn Prompting
The AI remembers and builds on previous messages in a conversation. It's useful for chatbots and agents.

**User:** "What's the capital of Spain?"  
**AI:** "Madrid."  
**User:** "And what's the population?"  
**AI:** "Madrid has about 3.3 million people."

## 10. Prompt Chaining
You connect multiple prompts together to complete a task in steps. Each step feeds into the next.

**Step 1 Prompt:** "Summarize this article."  
**Step 2 Prompt:** "Now turn the summary into a tweet."

## 11. Context Window Management
This involves carefully selecting what information to include in the prompt so the AI stays focused and doesn't forget important details. It's like packing only what you need into a small suitcase.

**Example:** Only include the last 3 user questions and answers in a long conversation to keep the AI on track.

## 12. Instruction Tuning
This means giving the AI very clear and specific instructions in the prompt. It helps the AI follow your intent more accurately.

**Prompt:** "Summarize this article in 3 bullet points, each under 10 words."

## 13. Output Formatting Prompts
You tell the AI exactly how you want the answer to look. This is helpful when the output needs to be structured.

**Prompt:** "List the top 3 cities by population in this format:  
1. City - Population"

## 14. Guardrail Prompting
You add rules or limits in the prompt to prevent the AI from going off-topic or giving unsafe answers.

**Prompt:** "Answer only with facts. Do not give opinions or guesses."

## 15. Reflection Prompting
The AI is asked to review or critique its own answer before finalizing it. This can improve accuracy and reasoning.

**Prompt:** "Here's your answer. Now check if it makes sense and correct any mistakes." 