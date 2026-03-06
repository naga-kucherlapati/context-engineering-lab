# Same Prompt, Different Context

This example shows how the same prompt can produce very different outputs depending on the context provided to the system.

The prompt itself does not change.

---

## The Prompt

Explain the key risks of using AI in decision making.

---

## Context A: No additional context

The system receives no information about:
- the audience
- the industry
- the stakes
- the decision environment

Result:

The response is generic and high level. It may mention bias, hallucination, and data issues, but the guidance remains abstract and difficult to act on.

---

## Context B: Business leadership context

The system receives additional context:

Audience: senior business leaders  
Industry: regulated enterprise  
Goal: decision support rather than full automation  
Constraint: avoid technical jargon

Result:

The response becomes more practical. It focuses on governance, accountability, and oversight. The explanation connects AI risks to leadership decisions and operational controls.

---

## Context C: Student learning context

The system receives different context:

Audience: university students  
Goal: learning and awareness  
Constraint: simple explanations and examples  
Exclusion: avoid legal or regulatory advice

Result:

The response becomes more educational. It uses simple language and examples that help students understand the topic without assuming industry knowledge.

---

## What this demonstrates

The improvement does not come from rewriting the prompt.

It comes from clarifying context.

This is why context engineering plays a central role in building reliable AI systems.
