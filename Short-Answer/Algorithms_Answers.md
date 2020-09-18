#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) The runtime for this algorithm is O(n). Since the while loop goes until a is greater or equal to n^3 and inside the while loop a is added to n^2. Cubing something means you multiply the number by iteself 3 times. When added n^2 to itself it'll take n times for a to be equal or greater to n^3.

b) The outer loop will run n times. The inner loop will run log n times. So to find the total runtime complexity we multiply the runtime of the outside loop with the runtime of the inside loop. Overall the runtime complexity for this algorithm is O(n log n)

c) The if statement at the beginning of the function is constant time and thus won't impact the overall runtime complexity. The runtime is dependent on the recursive call for bunnyEars(bunnies - 1). Since we are only subtracting 1 from n each time and going until n == 0. The total runtime will be O(n) since n - n is equal to 0, since we are only removing 1 each time it'll take n times to get to 0.

## Exercise II
