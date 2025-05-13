# Writesomething.ai - a writing buddy and cheerleader for beginner writers.


- A public (or otherwise shared) link to a GitHub repo that contains:
  - A 5-minute (or less) Loom video of a live demo of your application that also describes the use case.
  - A written document addressing each deliverable and answering each question.
  - All relevant code.
- A public (or otherwise shared) link to the final version of your public application on Hugging Face (or other).
- A public link to your fine-tuned embedding model on Hugging Face.

---

## TASK ONE – Problem and Audience

**Questions:**

- What problem are you trying to solve?  
  - Why is this a problem?  
- Who is the audience that has this problem and would use your solution?  
  - Do they nod their head up and down when you talk to them about it?  
  - Think of potential questions users might ask.  
  - What problem are they solving (writing companion)?

**Deliverables:**

- Write a succinct 1-sentence description of the problem.
- Write 1–2 paragraphs on why this is a problem for your specific user.

---

## TASK TWO – Propose a Solution

**Prompt:**  
Paint a picture of the “better world” that your user will live in. How will they save time, make money, or produce higher-quality output?

**Deliverables:**

- What is your proposed solution?  
  - Why is this the best solution?  
  - Write 1–2 paragraphs on your proposed solution. How will it look and feel to the user?  
  - Describe the tools you plan to use in each part of your stack. Write one sentence on why you made each tooling choice.

**Tooling Stack:**

- **LLM**  
- **Embedding**  
- **Orchestration**  
- **Vector Database**  
- **Monitoring**  
- **Evaluation**  
- **User Interface**  
- *(Optional)* **Serving & Inference**

**Additional:**  
Where will you use an agent or agents? What will you use “agentic reasoning” for in your app?

---

## TASK THREE – Dealing With the Data

**Prompt:**  
You are an AI Systems Engineer. The AI Solutions Engineer has handed off the plan to you. Now you must identify some source data that you can use for your application.

Assume that you’ll be doing at least RAG (e.g., a PDF) with a general agentic search (e.g., a search API like Tavily or SERP).

Do you also plan to do fine-tuning or alignment? Should you collect data, use Synthetic Data Generation, or use an off-the-shelf dataset from Hugging Face Datasets or Kaggle?

**Task:**  
Collect data for (at least) RAG and choose (at least) one external API.

**Deliverables:**

- Describe all of your data sources and external APIs, and describe what you’ll use them for.  
- Describe the default chunking strategy that you will use. Why did you make this decision?  
- *(Optional)* Will you need specific data for any other part of your application? If so, explain.

---

## TASK FOUR – Build a Quick End-to-End Prototype

**Task:**  
Build an end-to-end RAG application using an industry-standard open-source stack and your choice of commercial off-the-shelf models.

**Deliverables:**

- Build an end-to-end prototype and deploy it to a Hugging Face Space (or other endpoint).
![Conceptual Flow of Agentic RAG](ConceptualFlow.png)

---

## TASK FIVE – Creating a Golden Test Dataset

**Prompt:**  
You are an AI Evaluation & Performance Engineer. The AI Systems Engineer who built the initial RAG system has asked for your help and expertise in creating a "Golden Dataset" for evaluation.

**Task:**  
Generate a synthetic test dataset to baseline an initial evaluation with RAGAS.

**Deliverables:**

- Assess your pipeline using the RAGAS framework including key metrics:  
  - Faithfulness  
  - Response relevance  
  - Context precision  
  - Context recall  
- Provide a table of your output results.  
- What conclusions can you draw about the performance and effectiveness of your pipeline with this information?

---

## TASK SIX – Fine-Tune the Embedding Model

**Prompt:**  
You are a Machine Learning Engineer. The AI Evaluation & Performance Engineer has asked for your help to fine-tune the embedding model.

**Task:**  
Generate synthetic fine-tuning data and complete fine-tuning of the open-source embedding model.

**Deliverables:**

- Swap out your existing embedding model for the new fine-tuned version.  
- Provide a link to your fine-tuned embedding model on the Hugging Face Hub.

---

## TASK SEVEN – Final Performance Assessment

**Prompt:**  
You are the AI Evaluation & Performance Engineer. It's time to assess all options for this product.

**Task:**  
Assess the performance of the fine-tuned agentic RAG application.

**Deliverables:**

- How does the performance compare to your original RAG application?  
- Test the fine-tuned embedding model using the RAGAS framework to quantify any improvements.  
- Provide results in a table.  
- Articulate the changes that you expect to make to your app in the second half of the course. How will you improve your application?
