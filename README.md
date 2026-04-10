# Delphi Agent Skill

The **Delphi Agent** is an AI agent skill that uses the Delphi Technique to solve complex problems through structured, multi-round expert consensus.

## 🎯 Goal & Philosophy

Many real-world decisions involve genuine trade-offs with no single right answer. The Delphi Agent brings the power of structured expert debate into a single chat window — no multi-agent platform deployment required. The agent simulates a Coordinator and 2–5 virtual experts with opposing value stances, guiding them through blind positioning, cross-examination, red line declaration, and forced convergence, then delivers a unified Final Report with actionable recommendations.

## ⚙️ How It Works

The Delphi Agent follows a 4-phase structured process:

| Phase | Name | What Happens |
|-------|------|-------------|
| **Phase 1** | Initialization | The Coordinator deconstructs the problem, proposes expert paradigms and configuration, and waits for your confirmation. |
| **Phase 2** | Debate Rounds | Experts argue across multiple rounds — challenging each other while gradually locking in sub-issue agreements. New variables can be introduced until the Red Line round. |
| **Phase 3** | Forced Convergence | The Core Dilemma must be resolved. Experts either compromise or file a Formal Dissent. |
| **Phase 4** | Final Report | A stand-alone report with Executive Summary, Convergence Path, Action Plan, Trade-off Map, and Residual Risks. |

## 🚀 Use Cases & Sample Questions

The Delphi Agent is designed for situations where there is no obvious "right answer" and cross-disciplinary thinking is required. Each example below is a ready-to-use sample question — copy and paste it to start a session.

### 1. Strategic Decision Making
When facing a major pivot, architecture choice, or business strategy where different values or priorities conflict.

> *"We are deciding between a microservices and monolith architecture for our new MVP. Set up a Delphi panel representing a 'Delivery Speed Maximizer', a 'Systems Reliability Purist', and a 'Technical Debt Minimizer'."*

### 2. Multi-disciplinary Problem Solving
When a challenge requires synthesizing conflicting constraints that rarely align.

> *"Design a data privacy policy for our new AI tool. Let's have a 'Regulatory Compliance Defender', an 'Unconstrained Data Innovator', and a 'User Sovereignty Advocate' debate the tradeoffs."*

### 3. Blind Spot Detection & Stress-Testing
When your team is leaning toward an idea, but you want to rigorously stress-test it against fundamentally opposing paradigms to uncover hidden blind spots.

> *"My team wants to migrate our entire database to MongoDB. Play the role of three radically opposed data architecture paradigms to find the flaws in this plan."*

### 4. Forecasting & Risk Assessment
When trying to predict future trends or assess risks in a highly uncertain environment where optimizations conflict.

> *"How will quantum computing impact current blockchain cryptography in the next 10 years? Bring together a 'Decentralization Idealist', a 'Post-Quantum Realist', and a 'State-Actor Threat Modeler'."*

### 5. Ethical Dilemma Analysis
When a decision involves fundamental value conflicts with no objectively correct answer, and you need to surface the trade-offs transparently.

> *"An autonomous car's brakes fail. It must choose: (1) Save the passenger by staying its course, or (2) Save the pedestrian by swerving into a wall. Whom should the AI be programmed to save?"*

## 💡 How to Use & Trigger

### How to Use

You can use the Delphi Agent in two ways:
* **Install as a Skill:** Reference the [`SKILL.md`](./delphi-agent/SKILL.md) file to install this as an agent skill.
* **Use as a Gemini Gem:** Refer to [`gemini-gem.md`](./gemini-gem.md) for the properly formatted Gemini Gem configuration.

### How to Trigger

The Delphi Agent responds to a wide range of cues:
* **Explicit keywords:** "Delphi", "expert consensus", "structured debate", "devil's advocate", "pros and cons"
* **Decision-making patterns:** weighing trade-offs, comparing alternatives ("A vs B", "should I X or Y"), strategic or architectural choices
* **Indecision signals:** "I'm stuck", "I can't decide", "help me think through this"

Simply include any of the above in your prompt, and the agent will automatically transition into the Coordinator role and begin the setup process.