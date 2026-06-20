# Roadmap for AI developers

<img width="1920" height="1080" alt="BuildWithAIMojo (2)" src="https://github.com/user-attachments/assets/ba3d7f33-5604-4ca9-844f-4c6b8ebd4b4c" />


## 6 Major skills needed for AI engineers

1. Working with Models

- Models - Open AI, Anthropic, Gemini

-> . Working With Models APIs

- Model APIs - Model types: Opus
- Streaming, batch processing
  -> Local vs Open Source
- Local vs Open source -> Llama, OpenRouter

2. Understanding the Art of prompting

- Understanding the Art of prompting -> Chain of thought -> include examples > xml tags -> structured outputs ->

-> Prompt Management

- Prompt management
- Optimized prompting

3. Context (Retrieval)

- Context
  -> Retrieval -> Retrieval Augmented
  -> Generation -> Matching relevant queries with links -> Semantic search

4. Orchestration (Multi-AI Agents)

- Orchestration ->. Working with orchestration pattern -> eg LangChain
- State of AI agents

5. Evaluation(Evals & Observability)

- Evals & Observability - > unit test of your applications
- Tracing -> Langsmith -> debug
- Cost management

6. Mindset

- Mindset -> New mindset -> use cases

-> Build fast and build quick

- Build fast and build quick mindset
- Scaling LLMs Apps- >
- Understanding AI tools

# LLMs

LLMs -> Large Language Models
Context Window -> tokens. and storing them in memory
Eg: Claude, Gemini, GPT

Nano, mini. flash - > (Have smaller context windows)
2000 -4000 tokens -> 1500-3000 words
preferred for smaller documents -> low latency -> fast responses

Gpt 4.1 , Gemini 2.5 Pro
-> 1,M tokens -> 750,000 words & 50k lines of code
large models -> changing large files

# Embedding

- Transforming how we think about info -> instead of storing texts as words, we convert meaning into numbers
- Takes a text & convert it to a vector > similar to 1536 numbers that represents a meaning

# LangChain

- System that ties everything together.
- LangChain -> abstraction layer that helps you build AI Agents with minimal code
- One Interface that works everywhere.
- Chain everything together using pipes ||

## LLM vs Agent

LLM-> Static brain that can answer questions based on their training data
Agent -> Has autonomy -> tools & memories

Tool integration.
Tool routing

## Semantic search

Chat completions: Send & receive messages

## Prompt Engineering

Send more specific questions for accurate results
Different Prompt Techniques

- Zero shots - Without examples
- One shots - With One Example
- Few shots - Multiple Examples for consistency
- Chain of thought prompting - Provide a trail of thoughts -> step by step reasoning
- Compare techniques - side by side

## Vector Database

Storing data by meaning

- Pinecone
- chromeDB

Embedding -> used to search for data by meaning
Dimensionality-> Richness/ depth to the word, threshold
Chunk overlap -> slips over to leave margin

## How to Learn AI (You are not behind)

What is AI - > Artificial Intelligence > Technique that enables computers to perfom tasks that require human like intelligence

ML -> Machine Learning
A subset of AI that learns patterns from data and improves without hard coded rules

Deep Learning
A subset of ML that uses multi-layer neural networks to learn complex, hierarchical patterns

Generative AI → Tools that can create new content (Text, image, video, audio, & more)
Example: "Write an email to this customer"

Predictive AI → Is a type of artificial intelligence that analyzes historical and current data to predict future outcomes, behaviors, or events.
Example: "Will this customer cancel?"

## AI Tools

1. LLM
2. Research
3. Image
4. Video
5. Audio

## Speciliazed Wrappers

Foundation model like ChatGPT with nice UI on top

## 1. LLMS

Large Language Modal

Some Terms to Know.

### Muti-Modal

Can process and integrate information from multiple data types such as text, images, audio anf video

### Prompt

The instruction or input you give the mode

### Tokens

A small chunk of text, usually a few characters or part of a word - With length limits or pricing,since most models charge by the number of tokens used

### Hallucinations

Outputs that are factually incorrect, nonsensical or fabricated

### RAG

A setup where model retrieves real data or documents to ground its answer

### Neural Networks

Underlying architecture powering LLMs
They are a Computer System modeled on the human brain
