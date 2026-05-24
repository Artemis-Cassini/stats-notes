### Facts about Theoretical Probabilities 
- If the probability will not happen, we call such a "not event" a **complement**
	- The complement of the event "it rains today" is the event "it does not rain today"

**Summary of Probability Rules
- **Rule 1** - A probability is always a number from 0 to 1 (or 0% to 100%) inclusive (which means 0 and 1 are allowed). It may be expressed as a *fraction*, a *decimal*, or a *percentage*
	- In symbols - For any event A
		- 0 ≤ P(A) ≤ 1
- **Rule 2** - The probability that an event will not occur is 1 minus the probability that the event will occur
	- In symbols - For any event A
		- P(A does *not* occur) = 1 - P(A does occur)
	- The symbol A^c is used to represent the complement of A. With this notation we can write Rule 2 as
		- P(A^c) = 1 - P(A)

### Finding Theoretical Probabilities with Equally Likely Outcomes
- A list that contains *all* possible (and equally likely) outcomes is called the **sample space**, often referred to with the letter S
- An **event** is any collection of outcomes in the sample space

**Summary of Probability Rules**
- **Rule 3** 
	- Probability of A = P(A) = Number of outcomes in A/Number of all possible outcomes
- This is true *only* for equally likely outcomes

### Combining Events with "AND" and "OR"
- Another way to visualize a situation is with a **Venn diagram**, the rectangle represent the sample space, which consists of all possible outcomes, the ovals represent events
- The word **AND** creates a new event out of two other events

### Using "OR" to Combine Events
- In statistics and probability, we use the **inclusive OR**. For example, the people in the photo were asked to raise their hands if they had a hat OR glasses

### Mutually Exclusive Events
- When two events have no outcomes in common--that is, when it is impossible for both events to happen at once--they are called **mutually exclusive events**

**Summary of Probability Rules**
- **Rule 4** - The probability that event A happens OR event B happens is
	- (the probability that A happens) plus (the probability that B happens) minus (the probability that both A AND B happen)
- If A and B are mutually exclusive events (for example, A is the event that the selected person is single, and B is the event that the person is married), then P(A AND B) = 0. In this case, the rule becomes simpler
- **Rule 4a** - If A and B are mutually exclusive events, the probability that event A happens OR event B happens is the sum of the probability that A happens and the probability that B happens
	- Rule 4 in symbols
		- Always: P(A OR B) = P(A) + P(B) - P(A AND B)
	- Rule 4a in symbols
		- Only if A and B are mutually exclusive: P(A OR B) = P(A) + P(B)