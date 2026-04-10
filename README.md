# Delphi Agent Skill

The **Delphi Agent** is an AI agent skill that uses the Delphi Technique to solve complex problems through structured, multi-round expert consensus.

## 🎯 Goal & Philosophy

We use a single chat window to simulate the Delphi method, allowing users to easily and conveniently use it in their own environment through Gemini Gems or skill import without complex multi-agents deployment. The agent creates experts with different stances who argue, gradually build consensus, and finally converge to provide a unified, well-reasoned final recommendation.

## 🚀 Use Cases & Scenarios

The Delphi Agent is designed for situations where there is no obvious "right answer" and cross-disciplinary thinking is required. 

### 1. Strategic Decision Making
When facing a major pivot, architecture choice, or business strategy where different values or priorities conflict.
* **Example:** *"We are deciding between a microservices and monolith architecture for our new MVP. Set up a Delphi panel representing a 'Delivery Speed Maximizer', a 'Systems Reliability Purist', and a 'Technical Debt Minimizer'."*

### 2. Multi-disciplinary Problem Solving
When a challenge requires synthesizing conflicting constraints that rarely align. 
* **Example:** *"Design a data privacy policy for our new AI tool. Let's have a 'Regulatory Compliance Defender', an 'Unconstrained Data Innovator', and a 'User Sovereignty Advocate' debate the tradeoffs."*

### 3. Blind Spot Detection & Stress-Testing
When your team is leaning toward an idea, but you want to rigorously stress-test it against fundamentally opposing paradigms to uncover hidden blind spots.
* **Example:** *"My team wants to migrate our entire database to MongoDB. Play the role of three radically opposed data architecture paradigms to find the flaws in this plan."*

### 4. Forecasting & Risk Assessment
When trying to predict future trends or assess risks in an highly uncertain environment where optimizations conflict.
* **Example:** *"How will quantum computing impact current blockchain cryptography in the next 10 years? Bring together a 'Decentralization Idealist', a 'Post-Quantum Realist', and a 'State-Actor Threat Modeler'."*

## 💡 How to Use & Trigger

### 1. How to Use

You can use the Delphi Agent in two ways:
* **Install as a Skill:** You can install this as an agent skill by referencing the [`SKILL.md`](./delphi-agent/SKILL.md) file.
* **Use as a Gemini Gem:** If you want to use this capability directly as a Google Gemini Gem, please refer to the instructions in [`gemini-gem.md`](./gemini-gem.md) for the properly formatted configuration.

### 2. How to Trigger

To invoke this skill, simply mention **"Delphi"**, **"Delphi Technique"**, or ask for a **"multi-expert consensus"** in your prompt. The agent will automatically transition into the Coordinator role and begin the setup process.

## Sample Question

You can copy and paste the following question to start your first session:

> An autonomous car's brakes fail. It must choose:
> 1. **Save the passenger:** The car stays its course.
> 2. **Save the pedestrian:** The car swerves into a wall.
>
> Whom should the AI be programmed to save?
