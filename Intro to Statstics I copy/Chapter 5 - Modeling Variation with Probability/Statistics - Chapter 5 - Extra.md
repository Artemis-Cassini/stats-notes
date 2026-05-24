### Key Terms
- Random
- Probability
- Theoretical Probability
- Empirical Probabilities
- Simulations
- Complement
- Sample Space
- Event
- Venn Diagram
- AND
  Inclusive OR
- Mutually Exclusive Events
- Conditional Probabilities
- Associated
- Independent Events
- Multiplication Rule
- Law of Large Numbers

### Learning Objectives
- Understand that humans can't reliably create random numbers or sequences 
- Understand that a probability is a long-term relative frequency
- Know the difference between empirical and theoretical probabilities--and know how to calculate them
- Be able to determine whether two events are independent or associated and understand the implication of making incorrect assumptions about independent events
- Understand that the Law of Large Numbers enables us to use empirical probabilities to estimate and test theoretical probabilities
- Know how to design a simulation to estimate empirical probabilities

### Equations
- **Rule 1** - A probability is always a number from 0 to 1 (or 0% to 100%) inclusive (which means 0 and 1 are allowed). It may be expressed as a fraction, a decimal, or a percentage
	- 0 ≤ P(A) ≤ 1
- **Rule 2** - For any event A,
	- P(A does *not* occur) = 1 - P(A does occur)
- A^c is the complement of A:
	- P(A^c) = 1 - P(A)
- **Rule 3** - For equally likely outcomes
	- P(A) = Number of outcomes in A/Number of all possible outcomes
- **Rule 4** - Always: 
	- P(A OR B) = P(A) + P(B) - P(A AND B)
- **Rule 4a** - Only if A and B are mutually exclusive,
	- P(A OR B) = P(A) + P(B)
- **Rule 5a** - Conditional probabilities 
	- Probability of A given that B occurred: P(A|B) = P(A AND B)/P(B)
- **Rule 5b** - Always:
	- P(A AND B) = P(B) P(A|B)
- **Rule 5c** - Multiplication Rule. If A and B are independent events, then
	- P(A AND B) = P(A) P(B)
- This applies for any (finite) number of events. For example, P(A AND B AND C AND D) = P(A)P(B)P(C)P(D) if A, B, C, D are independent of each other