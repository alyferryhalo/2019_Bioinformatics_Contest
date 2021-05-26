# Bee Population

Alex starts to grow a bee population. Since he cannot account for all the bees, he decides to count the amount of the bees in kilograms! Each day the population of bees evolves. Initially, on the first day, there were *n1* kilograms of the bees. Suppose that at the *i*-th day the amount of bees is *n<sub>i</sub>* kilograms then on the next day the number of bees can be calculated by the following rule:

n<sub>i+1</sub> = a * n<sub>i</sub> - b * n<sub>i</sub>²

Alex now wonders what is the size of the population if he grows it indefinitely. Please, help him.

## Input format

The first line of the input contains one integer T T T (1≤T≤50) −         (1 \leq T \leq 50)\,-                 (1≤T≤50)−         the number of test cases.

Each of the next T T T lines contains a description of a test case. It consists of three real numbers with no more than three digits after the decimal point n1 n_1 n1​, a a a and b b b  − \,- − the size of the initial generation and the trend constants (0≤n1≤10, 0 \le n_1 \le 10, 0≤n1​≤10, 0≤a,b≤3 0 \leq a, b \leq 3 0≤a,b≤3).


## Output format

The i i i-th line of the output should contain the limit (in the mathematical sense) of the population size in kilograms in the i i i-th test. If there is no limit output "−1 -1 −1".

Your answer will be considered correct if its absolute or relative error doesn't exceed 10−4 10^{-4} 10−4.
