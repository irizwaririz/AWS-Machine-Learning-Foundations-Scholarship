## Test your knowledge with the following questions about Lesson 4: Software engineering practices, Part 1

NOTES: 

**The questions might provide clues to the previous questions so skipping questions might ruin the experience.**

**Since this lesson is about software engineering practices, it is best to practice these concepts on actual code as well. This is because the quiz will surely ask questions about specific coding scenarios that won't be covered by the questions below:**

* In your own words, define what clean code is.
    <details>
      <summary>Show answer</summary>

      Clean code is simple, concise, and readable code.

    </details>

* In your own words, why do we want to make modular code?
    <details>
      <summary>Show answer</summary>

      Because (1) it prevents writing extra unnecessary code (reusability) and (2) it helps to improve the readability of code (allows developers to understand and find relevant code easier).

    </details>

* What do you call code/software running on production servers being used by our clients/users?
    <details>
      <summary>Show answer</summary>

      Production code/software

    </details>

* In your own words, what is production-quality code?
    <details>
      <summary>Show answer</summary>

      Code that meets expectations for production in terms of reliability, and efficiency among other things.

    </details>

* In your own words, define "Refactoring code".
    <details>
      <summary>Show answer</summary>

      It is the restructuring of code to improve internal structure and/or improve efficiency without changing external functionality.

    </details>

* Why do we refactor code when it does no change to the external functionality?
    <details>
      <summary>Show answer</summary>

      Because it makes the code easier to maintain which reduces workload in the long run.

    </details>

* When writing clean code, we should assign meaningful names to our variables. How do we imply the type of a variable? (functions vs variables, booleans)
    <details>
      <summary>Show answer</summary>

      We should assign verbs for functions and nouns for variables. We should also assign is- or has- prefixes to variables that are booleans.

    </details>

* What Python Enhancement Proposal (PEP) proposed the standard style guide for Python code?
    <details>
      <summary>Show answer</summary>

      PEP 8

    </details>

* Regarding writing modular code, what does DRY stand for? What does it mean?
    <details>
      <summary>Show answer</summary>

      Don't Repeat Yourself.

      It means that if you have two or more pieces of code that does the exact same thing, you should create a function/module and reuse that across all the occurrences instead.

    </details>

* True or False, arbitrary variable names are always NOT useful in functions.
    <details>
      <summary>Show answer</summary>

      False

      Arbitrary variable names can make the function code more readable when that variable can have 2 or more representations based on usage.

      For example:

      def flat_curve(arr, n):
        return [i + n for i in arr]

      vs

      def flat_curve(test_scores, n):
        return [i + n for i in test_scores]

      flat_curve can be used in other applications as well, not just in curving test scores and this may confuse developers.

    </details>

* You can make code more efficient through?
    <details>
      <summary>Show answer</summary>

      1. Reducing runtime and
      2. Reducing memory consumption

      There is usually a trade-off between these two. Which one to prioritize will depend on the context.

    </details>

* Why do we prefer vector operations over loops when possible?
    <details>
      <summary>Show answer</summary>

      Because it's faster since we are doing parallel operations at once instead of doing the operations one-by-one.

    </details>

* In your own words, explain the purpose of code documentation.
    <details>
      <summary>Show answer</summary>

      It can make code navigation easier. It can also help clarify complex parts of the code. It can also convey the decisions made for the code.

    </details>

* What are the 3 types of documentation?
    <details>
      <summary>Show answer</summary>

      1. Line level (inline comments)
      2. Function/module level (documentation strings AKA docstrings)
      3. Project level (README file)

    </details>

* To whom is the README file addressed to?
    <details>
      <summary>Show answer</summary>

      Potential users and/or contributors

    </details>