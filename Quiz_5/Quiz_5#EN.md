## Question 1
Which of the following statements correctly describes a precondition in "Design by Contract"?
- [ ] It defines the possible return values of a function.
- [ ] It describes the effects of the function on the state of the world.
- [ ] It defines the requirements that must be met before the function is executed.
- [ ] It describes invariants that remain unchanged during program execution.

---

## Question 2
What is one of the main purposes of an interface?
- [ ] To ensure that all modules use the same code.
- [ ] To provide a clear separation between usage and implementation.
- [ ] To define all possible return values of a function.
- [ ] To prevent different modules from communicating with each other.

---

## Question 3
What does it mean to strengthen a postcondition?
- [ ] To increase the number of acceptable inputs.
- [ ] To loosen the requirements for inputs.
- [ ] To reduce the range of guaranteed return values.
- [ ] To add additional precondition requirements.

---

## Question 4
What property should a module have to be considered "modular"?
- [ ] It should use as many global variables as possible.
- [ ] It should not allow communication with other modules.
- [ ] It should not require a precondition.
- [ ] It should be self-contained and connected through precise interfaces.

---

## Question 5
What is achieved by weakening a precondition?
- [ ] Allowing fewer implementations.
- [ ] Reducing the guaranteed range of return values.
- [ ] Increasing the number of possible return values.
- [ ] Making a function usable with more possible input values.

---

## Question 6
What does an invariant describe in the context of Design by Contract?
- [ ] Conditions that must be met before and after a function.
- [ ] Guarantees about return values.
- [ ] Properties that remain unchanged throughout program execution.
- [ ] Requirements for the inputs of a function.

---

## Question 7
The following Scala code is given:

```scala
def sumOverDoubledList(lst: Array[Int]): Int = {
    var result: Int = 0
    val doubledList: Array[Int] = lst.map(x => 2 * x)
    for (i <- doubledList) {
      result += i
    }
    result
  }
```

1. Describe a contract for this function as a comment directly in the code. (No require or ensuring is necessary.)
2. Does the principle of weakest precondition/strongest postcondition apply here?