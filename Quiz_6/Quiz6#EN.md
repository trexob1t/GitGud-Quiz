# Quiz: Testing and Design Principles

## Question 1: What is the main goal of unit tests?
- [ ] To test the entire system in an integrated manner.
- [ ] To identify how the user interacts with the interface.
- [ ] To test the performance under heavy loads.
- [ ] To test individual components or functions in isolation.

---

## Question 2: What does "black box testing" focus on?
- [ ] Testing against a specification without knowing the internal structure.
- [ ] Testing internal structures or logic of the code.
- [ ] Measuring the performance and load of the system.
- [ ] Simulating the user interface for behavior analysis.

---

## Question 3: Which of the following is an example of "boundary testing"?
- [ ] Testing with randomly selected inputs from a valid range.
- [ ] Testing at the edges of valid input ranges, e.g., 0, -1, max value.
- [ ] Testing every possible input value exhaustively.
- [ ] Testing with inputs unrelated to the specifications.

---

## Question 4: What is a key concept of the Single Responsibility Principle (SRP)?
- [ ] A class should have multiple responsibilities for flexibility.
- [ ] A class should focus on inheritance over composition.
- [ ] A class should contain as few methods as possible.
- [ ] A class should have only one reason to change.

---

## Question 5: Which problem does violating SRP cause?
- [ ] It makes the code too cohesive.
- [ ] It introduces multiple reasons for the code to change.
- [ ] It ensures easier debugging.
- [ ] It prevents dependency injection from being applied.

---

## Question 6: How does the Open-Closed Principle guide software design?
- [ ] A module should be open for extension but closed for modification.
- [ ] A module should always be editable for adaptability.
- [ ] A module should avoid abstractions for faster development.
- [ ] A module should prioritize runtime changes over compile-time safety.

---

## Question 7: Why should modules avoid frequent modifications?
- [ ] It hinders backward compatibility.
- [ ] It can introduce new bugs and break dependent systems.
- [ ] It makes it harder to add new functionalities.
- [ ] It violates the Dependency Inversion Principle.

---

## Question 8: What is an example of complying with the Open-Closed Principle?
- [ ] Writing a new module that modifies existing functionality.
- [ ] Extending the behavior of a module through inheritance or composition.
- [ ] Refactoring the source code of a module to add features.
- [ ] Abstracting potential variations to allow extensions without altering the base code.

---

## Question 9: Black Box Testing
Consider following function:

```scala
def concat(string1: String, string2: String): String = {
    if(string1 == null || string2 == null) return ""
    string1.concat(string2)
    string1
}
```

Identify equivalence classes that can be used to test this function effectively.

