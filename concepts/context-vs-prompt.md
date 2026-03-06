# Context Engineering vs Prompt Engineering

Prompt engineering focuses on how a question is written.

Context engineering focuses on everything surrounding that question.

In real AI systems, the quality of answers depends far more on context than on clever wording.

---

## What prompt engineering does

Prompt engineering focuses on phrasing.

Examples include:
- Asking the model to act as a role
- Specifying format requirements
- Providing step-by-step instructions
- Controlling tone or output style

These techniques can improve responses, but they do not change what the system actually knows.

---

## What context engineering does

Context engineering shapes the information environment of the system.

It determines:
- What data the model can access
- What documents are retrieved
- What rules and constraints exist
- What memory is available
- What tasks the system is allowed to perform

Instead of asking better questions, context engineering ensures the system is operating with the right information and boundaries.

---

## Why context matters more

Most reliability problems in AI systems are not caused by bad prompts.

They are caused by:
- Missing information
- Incorrect or outdated data
- Conflicting instructions
- Lack of constraints
- No mechanism for verification

When context improves, output quality improves even with simple prompts.

---

## A practical way to think about it

Prompt engineering asks:

How should the question be written?

Context engineering asks:

What should the system know  
What should it not know  
What decisions should never be automated

The second set of questions is where most real system design happens.
