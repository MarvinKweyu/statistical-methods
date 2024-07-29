# Continuous distributions

### **Normal distribution / Gaussian distribution**

Properties of a normal distribution:

* The mean, median and mode are the same.
* The distribution is symmetric about the mean.



[Understanding the Normal Distribution](https://www.youtube.com/watch?v=IhtmW28slDw\&ab\_channel=365DataScience)

[Standard Normal distribution](https://www.youtube.com/watch?v=coA8gz9Uacg)

[How To Find The Z Score, Confidence Interval, and Margin of Error for a Population Mean](https://www.youtube.com/watch?v=DT-fPG0Hff8\&ab\_channel=TheOrganicChemistryTutor)

[Standard Normal Distribution Tables, Z Scores, Probability & Empirical Rule - Stats](https://www.youtube.com/watch?v=CjF\_yQ2N638\&t=125s\&ab\_channel=TheOrganicChemistryTutor)

[Hypothesis Testing Problems - Z Test & T Statistics - One & Two Tailed Tests 2](https://www.youtube.com/watch?v=zJ8e\_wAWUzE\&t=3s\&ab\_channel=TheOrganicChemistryTutor)

**Summary**

Represented as:

$$
X \sim N(\mu, \sigma)
$$

\
Read as: X follows a normal distribution with mean miu and standard deviation sigma.

Probability distribution function:\


$$
P(X) = \frac{1}{{\sqrt{2\pi \sigma^2}}}e^{score} \\ \\ where: \\ score = { - \frac{ {(x - \mu)}^2}{2\sigma^2}} \\
$$

(score has been split from the main function for brevity and ease of reading)

Expected value and variance:

$$
E(X) = \mu \\ \\ Variance(x) = \sigma^2
$$

**Exercises**

[Statlect](https://www.statlect.com/probability-distributions/normal-distribution)

### **Bernoulli distribution**

[Bernoulli Distribution](https://www.youtube.com/watch?v=nl9WiZMZnYs\&list=PLaFfQroTgZnzbfK-Rie19FdV6diehETQy\&index=5\&ab\_channel=365DataScience)

**Summary**

$$
X \sim Bern(p)
$$

Read as X follows a Bernoulli distribution with a probability of success **p**

Probability distribution function

$$
P(Y) = p^y(1-p)^{1-y}
$$

Usually events with one trial and two possible outcomes such as:

* A coin flip(heads or tail)
* A quiz (either pass or fail)

Expected value(mean)\


$$
E(x) = p
$$

Variance:

$$
\sigma ^2 = p(1-p)
$$

### **Binomial distributions**

[Probability: Binomial Distribution](https://www.youtube.com/watch?v=\_FbZI9mtSSM\&list=PLaFfQroTgZnzbfK-Rie19FdV6diehETQy\&index=4\&ab\_channel=365DataScience)

**Summary**

A sequence of identical Bernoulli events.

_Think of this as a bin of goodies. In this case, a bin of Bernoulli._

likely-to-succeed

$$
X \sim B(n, p)
$$

Read as: X follows a binomial distribution with **n** trials and a likely-to-succeed **p** on each trial.

A binomial distribution can also relate to a Bernoulli distribution as a binomial distribution with 1 trial as below:\


$$
Bern(p) = B(1, p)
$$

Probability function

$$
p(y) = \binom ny . p^y . (1-p)^{n-y}
$$

Expected value - that is, the mean

$$
E(x) = np
$$

Variance:

$$
\sigma ^ 2= np(1 - p)
$$

### **Chi-Squared distribution**

An asymmetric distribution that only has positive values

### **Exponential Distribution**

Events that are rapidly changing.

### **Logistic Distribution**

Used in forecast analysis. An example is the prediction of victory in a sporting event.

\
