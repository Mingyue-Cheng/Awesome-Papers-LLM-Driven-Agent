# Awesome Papers on LLM-Driven Agents

<div align="center">
  <img src="https://github.com/user-attachments/assets/ee4d1715-1a7d-44cf-8693-4326347c42c5" alt="Logo" width="300"/>
</div>


This repository curates a collection of cutting-edge research papers on **Large Language Model (LLM)-driven agents**, with a focus on their theoretical foundations, technological advancements, and practical applications. 

## Definition of an Agent

An **agent** is broadly defined as an entity that **perceives its environment through sensors** and **acts upon that environment through actuators** to achieve specific goals. In the context of LLM-driven agents, this perception-action loop is facilitated by the capabilities of large language models, enabling the agent to reason, plan, and act autonomously or collaboratively.

---

## Framework for LLM-Driven Agents

This repository categorizes papers into two key domains based on the structure and collaboration style of agents:

### 1. **Agent-related Techniques**
Single-agent systems focus on individual agents leveraging LLMs to perform complex tasks independently. These systems typically involve the following core components:

#### 1.1 Complex Task Reasoning
- **Planning:** Structured decomposition and execution of multi-step tasks, such as hierarchical task planning or tree-based reasoning.
   - **Related Paper:** *“ReAct: Synergizing Reasoning and Acting for Complex Decision-Making”* (2023), which introduces ReAct, a framework for integrating reasoning and action within a single-agent model. This work highlights the importance of structured task decomposition and planning to achieve complex problem-solving in LLMs.
  
- **Thought:** Techniques like **Chain-of-Thought (CoT)** prompting to enhance multi-step reasoning in LLMs.
   
- **Deliberation:** Methods for iterative refinement of actions or solutions based on intermediate results.

#### 1.2 Interaction with the External Environment
- **Action and Tool Use:** Integrating external APIs, retrieval-augmented generation (RAG), and dynamic resource utilization for enriched task-solving.
  
- **Feedback Integration:** Learning from external feedback, such as reinforcement signals or user interactions, to iteratively improve task performance.

#### 1.3 Autonomous Learning and Evolution
- **Self-Reflection and Critique:** Mechanisms for autonomous evaluation of task outcomes and identification of errors.
  
- **Self-Improvement:** Updating internal models or strategies based on observed shortcomings or feedback.

---
<div align="center">
  <img src="https://github.com/user-attachments/assets/9c3ab710-3e99-47dc-938f-ccf28fde6a61" alt="Logo" width="300"/>
</div>


### 2. **Multi-Agent Collaboration**
Multi-agent systems extend the capabilities of single agents by enabling collaborative behaviors among multiple LLM-driven agents. This collaboration can be categorized as follows:

#### 2.1 Distributed Problem Solving
- **Task Decomposition and Allocation:** Splitting a complex task into subtasks and assigning them to specialized agents for parallel execution.

- **Consensus Mechanisms:** Protocols for agents to reach agreement on shared goals or outcomes, such as voting or negotiation frameworks.

#### 2.2 Emergent Cooperation
- **Role Differentiation:** Assigning distinct roles (e.g., planner, executor, critic) to agents within the same environment to foster complementary expertise.
  
- **Communication Strategies:** Developing efficient and context-aware communication protocols to exchange information or coordinate actions.

#### 2.3 Agent Societies
- **Simulated Social Behavior:** Modeling interactions inspired by human social systems, such as collaborative problem-solving or competitive environments.

- **Multi-Agent Reinforcement Learning:** Training agents in cooperative or adversarial settings to optimize group-level objectives.

---

### 3. **Agent Applications**
<div align="center">
  <img src="https://github.com/user-attachments/assets/bc0f72f6-e94c-4abd-a37d-a672c5583552" alt="Logo" width="300"/>
</div>




LLM-driven agents are increasingly finding applications in a variety of domains, solving real-world problems with their reasoning, planning, and action-taking capabilities. Some notable application areas include:

#### 3.1 **Healthcare Applications**
- **Medical Diagnosis Support:** LLM agents assist healthcare professionals in diagnosing diseases by reasoning through complex medical data, interacting with medical knowledge bases, and suggesting potential diagnoses.

#### 3.2 **4Science Applications**
- **Medical Diagnosis Support:** LLM agents assist healthcare professionals in diagnosing diseases by reasoning through complex medical data, interacting with medical knowledge bases, and suggesting potential diagnoses.

#### 3.3 **Customer Support and Service**
- **Automated Customer Assistance:** LLM agents are used in customer service chatbots, providing automated support by understanding customer queries and generating contextually relevant responses.

---

## Contribution Guide

We welcome contributions to this repository, including:
1. **New Papers:** High-quality papers related to LLM-driven single or multi-agent systems.
2. **Reviews:** Summaries or critiques of existing papers to provide deeper insights.
3. **Applications:** Real-world implementations or case studies that demonstrate the utility of LLM-driven agents.

Please submit a pull request with your contribution and include a brief description of the addition.

---

## Acknowledgments

This repository was inspired by the rapid advancements in artificial intelligence and the transformative potential of LLMs in autonomous agent systems. Special thanks to the authors and researchers who have contributed to this exciting field.

---

With the new **Related Paper** terminology, the repository now highlights research that directly relates to the key topics in each section. Let me know if you'd like any further adjustments!
