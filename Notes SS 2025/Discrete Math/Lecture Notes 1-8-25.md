### Logic & Proofs - Chapter Summary
- Propositional logic
	- Applications
	- Logical Equivalencies
	- The language of propositions
- Predicate Logic
	- The Language of Quantifiers
	- Logical Equivalencies
	- Nested Quantifiers
- Proofs
	- Rules of Inference
	- Proof Methods
	- Proof Strategy


### Propositions
- Examples of Propositions:
	- All mathematicians wear sandals
	- Toronto is the capital of Canada
	- 1 + 0 = 1
	- 0 + 0 = 2
- Examples that are NOT Propositions:
	- Sit down!
	- What time is it?
	- x + 1 = 2
	- x + y = z

### Constructing Propositions
- Propositional variables:
$$
A, B, C, \dots, P, Q, \dots
$$
- Compound Propositions are constructed from logical connectives and other propositions
- Negation:
$$
\neg
$$

- Conjunction: The conjunction of propositions, A and B, is denoted 
$$
A \wedge B
$$
	- If one is false, the result is false. If both A and B are true, the statement is true. CS: "and"
- Disjunction: A disjunction of propositions, A and B, is denoted
$$
A\vee B
$$
	- If one is true, the result is true. If both A and B are false, the statement is false. CS: "or" <- nonexclusive
	- XOR would be represented as:
$$
A \oplus B \equiv (A \vee B) \wedge \neg(A \vee B)
$$

- Implication: The implication, or conditional statement of the propositions, A and B, is denoted 
$$
A \implies B
$$
	- In this context:
	- A is the hypothesis (antecedent or premise)
	- B is the conclusion(or consequence)
			- Example: If it is raining, then I will wear a hat
- Biconditional: The biconditional proposition of A and B is denoted:
$$
A\iff B \equiv (A \implies B) \wedge (B \implies A)
$$
	- A if and only if B