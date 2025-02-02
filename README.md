# Elixir Immutable List Modification in Enum.each
This example demonstrates a common mistake in Elixir when working with lists and the `Enum.each` function.  Because Elixir lists are immutable, attempts to directly modify a list inside an `Enum.each` loop will fail to produce the desired result.

The `bug.exs` file shows the erroneous code, while `bugSolution.exs` provides a corrected version using `Enum.filter` or list comprehensions for efficient immutability.
