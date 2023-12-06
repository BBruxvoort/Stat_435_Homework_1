# Stat_435_Homework_1

1) There are many simple experiments that can be performed to estimate π for a partic-
ular problem, and we encourage you to perform your own. The parts below discuss
some experiments that we or our students have performed in the past. For each part,
discuss conditions that are needed in order to satisfy the five assumptions for using
the binomial distribution outlined in Section 1.1.1.
(a) One of the first solid foods that infants can feed to themselves is the cereal
Cheerios. Early on, infants often lack the dexterity in their fingers to pick up
an individual Cheerio and put it into their mouth. In order to estimate the
probability of success for one infant, an experiment was designed where a Cheerio
would be set on an infant’s food tray for 20 successive trials at the dinner table.
If the Cheerio made it into the infant’s mouth, the response for the trial was
considered a success; otherwise, the response was considered a failure. Out of
these 20 trials, there were 9 Cheerios that made it into the infant’s mouth.
(b) In most billiards games, the person who breaks a rack of balls gets another turn
if at least one ball is sunk, excluding the cue ball. This is advantageous for this
person because there are a fixed number of balls that need to be sunk in order to
win a game. In order to estimate one person’s probability of success of sinking a
ball on the break, there were 25 consecutive breaks performed in 8-ball billiards.
Out of these 25, 15 breaks had a ball sunk.

2) Continuing Exercise 1, find the Wald, Agresti-Coull, Wilson, and Clopper-Pearson
intervals using the given data. Interpret the intervals in the context of the experiments.

3) Suppose that 79 out of 80 people contacted in a survey of city residents oppose a new
tax. Let π represent the probability that a randomly selected resident opposes the
tax.
(a) Compute a 95% Wald confidence interval for π. Interpret the results.
(b) Compute a 95% Wilson confidence interval for π. Interpret the results.
(c) Is it possible that π = 1? Explain.
(d) Which interval do you prefer? Explain.

4) The Wilson interval is found through equating
Z0 = ˆπ − π0
√π0(1 − π0)/n ,
to Z1−α/2 and solving for π0. Show that the solutions obtained are the Wilson interval
limits given in Section 1.1.2. Note that the quadratic formula will be helpful to
complete this problem.

5) There are many other proposed confidence intervals for π. One of these intervals
mentioned in Section 1.1.2 was the LR interval. Using this interval, complete the
following:
(a) Verify the 95% LR confidence interval is 0.1456 < π < 0.7000 when n = 10 and
w = 4. Note that binom.confint() calculates this interval using the methods =
"lrt" argument value. We also provide additional code to calculate the interval
in CIpi.R.
(b) Construct a plot of the true confidence levels similar to those in Figure 1.3. Use
n = 40 and α = 0.05, and vary π from 0.001 to 0.999 by 0.0005.
