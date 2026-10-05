# Week 01 Questions & Answers

---

## Q1. AI → ML → Deep Learning → Generative AI → Agents

### A - Answer
- **Artificial Intelligence (AI):** The overarching field of computer science dedicated to creating systems capable of performing tasks that typically require human intelligence, such as reasoning, problem-solving, and perception.
- **Machine Learning (ML):** A subfield of AI where algorithms analyze historical data to learn patterns and make predictions or decisions automatically without being explicitly programmed with fixed rules.
- **Deep Learning (DL):** A specialized subset of ML based on multi-layered artificial neural networks designed to process complex, unstructured data (like images, audio, or text).
- **Generative AI (GenAI):** A branch of Deep Learning focused on creating brand-new content (text, code, images, audio) by learning the underlying statistical structure of existing data.
- **AI Agent:** A system architecture or workflow that uses an AI model (like an LLM) as its central reasoning engine to autonomously make decisions, plan multi-step workflows, and execute actions using external tools.

#### Concept Map / Hierarchy Diagram

+-------------------------------------------------------------------+
| ARTIFICIAL INTELLIGENCE (AI)                                     |
|  Everyday Example: Chess engines (AlphaZero), Siri                |
|                                                                   |
|   +-----------------------------------------------------------+   |
|   | MACHINE LEARNING (ML)                                     |   |
|   |  Everyday Example: Email spam filtering                   |   |
|   |                                                           |   |
|   |   +---------------------------------------------------+   |   |
|   |   | DEEP LEARNING (DL)                                |   |   |
|   |   |  Everyday Example: Facial recognition unlock      |   |   |
|   |   |                                                   |   |   |
|   |   |   +-------------------------------------------+   |   |   |
|   |   |   | GENERATIVE AI (GenAI)                     |   |   |   |
|   |   |   |  Everyday Example: ChatGPT, Midjourney    |   |   |   |
|   |   |   +-------------------------------------------+   |   |   |
|   |   +---------------------------------------------------+   |   |
|   +-----------------------------------------------------------+   |
+-------------------------------------------------------------------+

---

## Q2. What is the difference between narrow AI and general AI?

### A - Answer
- **Narrow AI (Weak AI):** Designed to perform a specific task well, such as recommending products, recognizing faces, translating text, or responding to a chatbot prompt.
- **General AI (Strong AI):** A theoretical form of AI that can understand, learn, and perform any intellectual task at the level of a human. This remains an area of ongoing research and is not yet fully achieved.

**In simple terms:** Narrow AI is task-focused, while General AI is human-level intelligence across many domains.

---

## Q3. What is the difference between supervised, unsupervised, and reinforcement learning?

### A - Answer
- **Supervised Learning:** The model learns from labeled data, where each input has a known correct output. It is used for prediction and classification tasks.
- **Unsupervised Learning:** The model analyzes unlabeled data to find hidden patterns, structures, or clusters.
- **Reinforcement Learning:** The model learns by interacting with an environment and receiving rewards or penalties based on its actions. It is often used in game-playing and robotics.

**Example:**
- Supervised: Detecting spam emails using labeled examples.
- Unsupervised: Grouping customers by purchasing behavior.
- Reinforcement: Training an AI to play chess or a robot to navigate a room.

---

## Q4. What is a neural network?

### A - Answer
A neural network is a computational model inspired by the structure of the human brain. It consists of interconnected nodes (neurons) organized in layers. These networks learn patterns from data by adjusting the strength of connections between neurons.

**Key components:**
- Input layer
- Hidden layers
- Output layer
- Weights and biases
- Activation functions

Neural networks are the foundation of deep learning.

---

## Q5. What is generative AI and how is it different from traditional AI?

### A - Answer
**Generative AI** refers to AI models that can create new content based on patterns learned from training data. Examples include text generation, image generation, music generation, and code generation.

**Difference from traditional AI:**
- Traditional AI often focuses on classification, prediction, or decision-making.
- Generative AI focuses on creating new outputs that resemble the learned data distribution.

**Example:**
- Traditional AI: Predicting whether an email is spam.
- Generative AI: Writing a paragraph, generating an image, or creating a poem.

---

## Q6. What is a large language model (LLM)?

### A - Answer
A Large Language Model (LLM) is a type of AI model trained on massive amounts of text data to understand and generate human-like language. These models are capable of tasks such as answering questions, summarizing content, writing code, translating languages, and completing text prompts.

**Examples:**
- ChatGPT
- Claude
- Gemini
- Llama

LLMs are built using transformer architectures and are trained on large-scale text corpora.

---

## Q7. What is a transformer model?

### A - Answer
A transformer is a deep learning architecture designed to process sequential data, especially text, efficiently and effectively. It uses self-attention, which allows the model to decide which parts of the input are most relevant to each other.

**Why transformers matter:**
- They handle long-range dependencies well.
- They are scalable for huge datasets.
- They power modern LLMs and many multimodal systems.

**Key idea:** The model does not read text like a simple sequence; it learns relationships between all words in a sentence or document.

---

## Q8. What is hallucination in AI?

### A - Answer
AI hallucination happens when a model generates information that sounds believable but is actually incorrect, fabricated, or unsupported by the source data.

**Examples:**
- Making up a citation
- Inventing a historical fact
- Generating a wrong answer with confident wording

**Why it happens:**
- The model predicts the next token based on patterns, not truth verification.
- It may generate fluent but false information.

**Important:** AI outputs must always be checked, especially in academic, professional, or medical use cases.

---

## Q9. What is an AI agent?

### A - Answer
An AI agent is a software system that can reason about a goal, make decisions, and use tools or external systems to complete tasks. It usually combines:
- a language model for reasoning,
- memory or context management,
- tool use (like search, retrieval, APIs, code execution),
- a defined goal or workflow.

**Examples of AI agent tasks:**
- Researching a topic and summarizing findings
- Writing and debugging code
- Automating spreadsheet tasks
- Planning travel and booking flights
- Managing customer support workflows

**Difference from a chatbot:** A chatbot answers prompts; an agent can act with tools and complete multi-step tasks.

---

## Q10. What is prompt engineering and why is it important?

### A - Answer
Prompt engineering is the practice of designing effective inputs (prompts) to guide AI models toward better, more relevant, and more useful outputs.

**Why it matters:**
- It improves answer quality.
- It reduces ambiguity.
- It helps control tone, format, and structure.
- It enables stronger results for tasks like writing, coding, summarizing, and analysis.

**Examples of prompt techniques:**
- Be specific about the task
- Provide context and constraints
- Ask for step-by-step reasoning
- Request a desired format
- Provide examples when needed

**Example:**
Instead of asking, “Explain AI,” ask:
“Explain AI in simple language for a beginner, in 5 bullet points, with examples and limitations.”

---

## Final Reflection

AI literacy is not just about using tools like ChatGPT or Copilot. It includes understanding how these systems work, where they are useful, and where they can fail. A literate user learns to ask better questions, evaluate outputs critically, and use AI responsibly in learning and work.

This week focused on understanding the foundations of AI, the hierarchy from AI to agents, and the importance of evaluating AI systems carefully.
