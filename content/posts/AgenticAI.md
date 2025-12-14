+++
date = '2025-12-14'
draft = false
title = 'An Introduction To AI Agents'
+++

## What Are AI Agents?

An AI agent perceives its environment, makes decisions, and takes action to achieve a goal.  
Unlike a standard LLM that only responds to prompts, an agent acts with purpose, persistence, and awareness of its surroundings.

Think of an LLM as a skilled doctor with deep theoretical knowledge, and an AI agent as that doctor using instruments, labs, and hospital systems to examine patients and act in real time.  
The agent uses the LLM for reasoning but extends it with tools, APIs, and live data sources to plan and execute tasks autonomously.

---

## LLMs, RAGs, and AI Agents

### Standard LLMs
- Work as **sophisticated text prediction engines**
- Follow a single flow: `input → output`
- Have **no goals or memory** beyond the prompt
- Are **reactive**, responding only when prompted

### RAGs
- Extend LLMs by retrieving relevant information from **external sources**
- Use **vector databases, search engines, or knowledge graphs** to ground responses
- Improve **accuracy** and reduce **hallucinations**
- Still **reactive** and lack **autonomy** or long-term objectives

### AI Agents
- Use an **LLM as the brain**, but act beyond text prediction
- Maintain **ongoing goals** and **act without prompting**
- Connect to **tools, APIs, and systems** through frameworks like MCP
- Retain memory, plan multi-step tasks, and reason about outcomes
- Support **long-term, goal-oriented behavior**

---

## The Three Pillars of Agency

Every true agent stands on three pillars:

### 1. Goal-Directed Behavior
An agent has a clear purpose and works steadily toward it.

*Example:* A customer service agent aims not just to reply but to resolve customer issues with minimal human handover.

### 2. Interactive Capacity
Agents engage with their environment—databases, software systems, or the physical world.

*Example:* A scheduling agent doesn’t just suggest meeting slots. It checks your calendar, sends invites, and updates appointments.

### 3. Autonomous Decision-Making
Agents think and act without constant human input. They evaluate options, make choices, and take initiative.

*Example:* A research agent may decide which sources to explore, extract key points, and form new questions—on its own.

---

## Core Capabilities of AI Agents

For these pillars to hold, agents rely on several core capabilities:

### 1. Reasoning Mechanisms
Agents use multiple reasoning types:

- **Deductive:** Drawing logical conclusions  
  *If A is true, and A → B, then B must be true.*
- **Inductive:** Generalizing from patterns  
  *If X often leads to Y, X likely causes Y.*
- **Abductive:** Inferring best explanations  
  *Given symptoms A, B, and C, D is the most probable cause.*

> **Why Advanced Reasoning Works Today:**  
Modern LLMs have reached a level where reasoning becomes emergent. 
Beyond a particular scale(10^8 billion parameters), LLMs develop abilities like pattern recognition, implicit knowledge synthesis, and self-assessment—key traits that make agentic behavior possible.
You can read about emergent capabilities of LLMs in the [paper](https://arxiv.org/pdf/2206.07682).

### 2. Memory Systems
Agents need memory to think and act coherently:

- **Working Memory:** Keeps immediate context to handle multi-turn conversations and ongoing tasks.
- **Long-Term Memory:** Stores knowledge, learned patterns, and user preferences across sessions—often powered by vector databases or retrieval systems.

### 3. Autonomous Action
Acting independently separates agents from models.

- **Action Space:** The full set of possible actions—API calls, database queries, tool usage, or text generation.
- **Action Selection:** Choosing the best action for the goal, balancing exploration (trying new methods) and exploitation (using proven ones).


