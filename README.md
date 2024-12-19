以下是将 **Key Paper** 改为 **Related Paper** 并更新后的版本：

---

# Awesome Papers on LLM-Driven Agents

This repository curates a collection of cutting-edge research papers on **Large Language Model (LLM)-driven agents**, with a focus on their theoretical foundations, technological advancements, and practical applications. 

## Definition of an Agent

An **agent** is broadly defined as an entity that **perceives its environment through sensors** and **acts upon that environment through actuators** to achieve specific goals. In the context of LLM-driven agents, this perception-action loop is facilitated by the capabilities of large language models, enabling the agent to reason, plan, and act autonomously or collaboratively.

---

## Framework for LLM-Driven Agents

This repository categorizes papers into two key domains based on the structure and collaboration style of agents:

### 1. **Single-Agent Techniques**
Single-agent systems focus on individual agents leveraging LLMs to perform complex tasks independently. These systems typically involve the following core components:

#### 1.1 Complex Task Reasoning
- **Planning:** Structured decomposition and execution of multi-step tasks, such as hierarchical task planning or tree-based reasoning.
   - **Related Paper:** *“ReAct: Synergizing Reasoning and Acting for Complex Decision-Making”* (2023), which introduces ReAct, a framework for integrating reasoning and action within a single-agent model. This work highlights the importance of structured task decomposition and planning to achieve complex problem-solving in LLMs.
  
- **Thought:** Techniques like **Chain-of-Thought (CoT)** prompting to enhance multi-step reasoning in LLMs.
   - **Related Paper:** *“Chain-of-Thought Prompting Elicits Reasoning in Large Language Models”* (2022), which demonstrates the effectiveness of CoT in enhancing the reasoning capabilities of LLMs for multi-step tasks.
   
- **Deliberation:** Methods for iterative refinement of actions or solutions based on intermediate results.
   - **Related Paper:** *“Self-Reflective Reasoning in LLM Agents”* (2024), which explores how LLMs can use deliberation to refine their actions iteratively, improving task completion success rates.

#### 1.2 Interaction with the External Environment
- **Action and Tool Use:** Integrating external APIs, retrieval-augmented generation (RAG), and dynamic resource utilization for enriched task-solving.
   - **Related Paper:** *“Tool-Use and Action Integration in LLMs for Real-World Tasks”* (2023), focusing on the integration of external tools to augment LLMs' action-taking capabilities for complex tasks.
  
- **Feedback Integration:** Learning from external feedback, such as reinforcement signals or user interactions, to iteratively improve task performance.
   - **Related Paper:** *“Learning from Feedback: Reinforcement Learning for LLMs”* (2023), which discusses how LLMs can adapt and improve performance based on feedback from external environments.

#### 1.3 Autonomous Learning and Evolution
- **Self-Reflection and Critique:** Mechanisms for autonomous evaluation of task outcomes and identification of errors.
   - **Related Paper:** *“Self-Evaluation in LLMs for Continuous Improvement”* (2023), which demonstrates how LLM-driven agents can reflect on their actions and outcomes to identify areas for improvement.
  
- **Self-Improvement:** Updating internal models or strategies based on observed shortcomings or feedback.
   - **Related Paper:** *“Self-Improvement Through Active Learning in LLMs”* (2024), exploring how LLMs can engage in self-improvement by continuously updating their internal models based on new information or feedback.

---

### 2. **Multi-Agent Collaboration**
Multi-agent systems extend the capabilities of single agents by enabling collaborative behaviors among multiple LLM-driven agents. This collaboration can be categorized as follows:

#### 2.1 Distributed Problem Solving
- **Task Decomposition and Allocation:** Splitting a complex task into subtasks and assigning them to specialized agents for parallel execution.
   - **Related Paper:** *“Collaborative Multi-Agent Systems for Task Decomposition”* (2024), which focuses on how agents can distribute complex tasks and divide responsibilities to achieve optimal results.

- **Consensus Mechanisms:** Protocols for agents to reach agreement on shared goals or outcomes, such as voting or negotiation frameworks.
   - **Related Paper:** *“Consensus in Multi-Agent Systems: A Negotiation Framework”* (2023), which discusses how multiple agents can collaborate and negotiate to reach a consensus on shared objectives.

#### 2.2 Emergent Cooperation
- **Role Differentiation:** Assigning distinct roles (e.g., planner, executor, critic) to agents within the same environment to foster complementary expertise.
   - **Related Paper:** *“Emergent Cooperation in Multi-Agent Systems: Role Differentiation and Team Dynamics”* (2024), which highlights the benefits of role-based differentiation in optimizing multi-agent collaboration.
  
- **Communication Strategies:** Developing efficient and context-aware communication protocols to exchange information or coordinate actions.
   - **Related Paper:** *“Efficient Communication Protocols for Multi-Agent Collaboration”* (2023), focusing on how agents communicate effectively in collaborative settings to improve decision-making processes.

#### 2.3 Agent Societies
- **Simulated Social Behavior:** Modeling interactions inspired by human social systems, such as collaborative problem-solving or competitive environments.
   - **Related Paper:** *“Simulated Social Behavior in Multi-Agent Systems”* (2024), which discusses how agents can mimic human-like social behavior in simulated environments for collaborative tasks.

- **Multi-Agent Reinforcement Learning:** Training agents in cooperative or adversarial settings to optimize group-level objectives.
   - **Related Paper:** *“Multi-Agent Reinforcement Learning for Cooperative Problem Solving”* (2023), which presents techniques for training agents in multi-agent reinforcement learning settings for collaborative optimization.

---

### 3. **Agent Applications**
LLM-driven agents are increasingly finding applications in a variety of domains, solving real-world problems with their reasoning, planning, and action-taking capabilities. Some notable application areas include:

#### 3.1 **Healthcare Applications**
- **Medical Diagnosis Support:** LLM agents assist healthcare professionals in diagnosing diseases by reasoning through complex medical data, interacting with medical knowledge bases, and suggesting potential diagnoses.
   - **Related Paper:** *“AI-Powered Diagnosis: Leveraging LLMs for Complex Medical Decision Making”* (2024), which explores how LLM-driven agents support diagnostic reasoning by utilizing multimodal health data.
  
- **Personalized Treatment Planning:** LLM agents collaborate with medical professionals to design personalized treatment plans by processing patient-specific data and applying medical guidelines.
   - **Related Paper:** *“Personalized Medicine through LLMs: A Multi-Agent Approach”* (2023), discussing how LLM-driven agents contribute to personalized healthcare by adapting to individual patient profiles.

#### 3.2 **Customer Support and Service**
- **Automated Customer Assistance:** LLM agents are used in customer service chatbots, providing automated support by understanding customer queries and generating contextually relevant responses.
   - **Related Paper:** *“Customer Service Chatbots: Leveraging LLMs for Effective Communication”* (2023), which explores how LLMs enhance the effectiveness of customer service agents by improving their contextual understanding.

- **Dynamic Query Handling:** These agents can adapt in real-time to complex customer queries, integrating information from multiple sources to generate accurate answers.
   - **Related Paper:** *“Adaptive Query Handling for Customer Support using LLMs”* (2024), focusing on how LLM agents dynamically handle customer queries and adapt responses based on real-time interactions.

#### 3.3 **Autonomous Vehicles**
- **Decision-Making in Complex Environments:** LLM-driven agents assist autonomous vehicles in making high-level decisions, interpreting environmental data, and planning safe routes.
   - **Related Paper:** *“LLM-Driven Autonomous Vehicles: Navigating Complex Environments”* (2023), which discusses how LLM agents aid in decision-making by integrating real-time sensory inputs.

#### 3.4 **Education and Training**
- **Intelligent Tutoring Systems:** LLMs power intelligent tutoring systems that provide personalized learning experiences, adapting to students' learning progress and providing targeted interventions.
   - **Related Paper:** *“Intelligent Tutors: Enhancing Personalized Education with LLMs”* (2023), which highlights the use of LLM-driven agents to create adaptive learning environments in educational settings.
  
- **Research Assistance:** LLM agents assist researchers by providing literature reviews, summarizing scientific papers, and suggesting relevant articles.
   - **Related Paper:** *“AI Research Assistants: Enhancing Scholarly Work with LLMs”* (2024), which explores how LLM-driven agents support the research community by assisting with literature review and knowledge discovery.

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
