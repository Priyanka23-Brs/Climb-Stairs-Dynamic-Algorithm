## Climb Stairs

This algorithm takes an integer n as input and returns the number of ways to climb n stairs. The function works by maintaining two variables: firstStep and secondStep. firstStep stores the number of ways to climb n - 1 stairs, and secondStep stores the number of ways to climb n - 2 stairs.

The function starts by initializing firstStep and secondStep to 1. Then, the function iterates over the values of n from 2 to n. For each value of n, the function calculates the number of ways to climb n stairs as the sum of the number of ways to climb n - 1 stairs and the number of ways to climb n - 2 stairs. The function then updates firstStep and secondStep to store the number of ways to climb n - 1 stairs and n - 2 stairs, respectively. The function continues to iterate until it reaches n. At the end, the function returns the value of thirdStep, which is the number of ways to climb n stairs.

#### Check out the live app [here](https://priyanka23-brs.github.io/Call-Center/).
