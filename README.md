This repository contains a Hack program that demonstrates a stack overflow error caused by a recursive function. The recursive function `foo()` calculates the factorial of a number. When the input is large, the function calls itself many times, exceeding the call stack limit and causing a stack overflow error. The solution shows how to avoid this by using iteration.