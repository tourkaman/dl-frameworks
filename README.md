# dl-frameworks
Comparison: Style &amp; Performance

Starting with Flax, fast.ai, and Flux.

Haiku is also interesting. Haiku seems to be more object oriented as opposed to Flax which is (completely?) functional.

How about Sonnet? How does that one play into all of this?

## Considerations and nice-to-haves

Try to use the same library for optimization and loss functions if possible, across all of these comparisons, or at least build up a matrix where you list all of these frameworks against various optimization or helper libraries, so that you still maintain the consistency.

What would be really cool is if you automated this entire process, so that as new (versions of) frameworks and helper libraries came out you could very quickly spin up all the necessary experiments and test cases and gather new data on the performance results.
