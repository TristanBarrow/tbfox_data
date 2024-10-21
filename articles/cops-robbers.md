When I teach Test-Driven Development (TDD), I often use a "cops and robbers" analogy. In this game, the "cop" represents your test, setting rules for your code. The "robber" is your production code, trying its best to evade these rules.

Lets think through a simple example.

First, we start with a simple rule: "A function must exist." The cop demands it, so the robber complies, creating a function.

Next, requiring specific arguments for the function. The robber adapts, altering the function to meet these new demands.

The cop now focuses on outcomes. If the function should return the square root of 25 as 5, the robber must comply. At first, it might take shortcuts, directly returning 5. But as the cop introduces more tests, the robber evolves, eventually implementing the true square root algorithm.

This playful dance between cop and robber continues, refining your code until it adheres to all the rules you need to perform your task.

Despite how controversial it can be, I have found TDD to be an essential aspect of writing secure and sound systems. It takes getting used to and it is difficult at first but as you grow in your capabilities you'll find writing code without it to be unreasonably difficult.
