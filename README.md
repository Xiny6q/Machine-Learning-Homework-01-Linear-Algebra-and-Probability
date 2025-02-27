Download link :https://programming.engineering/product/machine-learning-homework-01-linear-algebra-and-probability/

# Machine-Learning-Homework-01-Linear-Algebra-and-Probability
Machine Learning Homework 01: Linear Algebra and Probability
1. ℓ2 Norm. (4 points) The ℓ2 norm of a vector x ∈ Rn is defined as

n

∥x∥2 =

xi2.

(1)

i=1

Show that it statisfies the following four properties

∥x∥2 ≥ 0 for any x ∈ Rn

∥x∥2 = 0 if and only if x = 0

∥ax∥2 = |a| · ∥x∥2 for any x ∈ Rn and a ∈ R

∥x + y∥2 ≤ ∥x∥2 + ∥y∥2, for any x, y ∈ Rn

Describe a random event using probabilistic language. (3 points) Pick a random event — any event that you are interested if there is some randomness. Even for the things that we know for sure, there may be some randomness. For example, we know for sure that the sun will rise every day, but the specific time of sunrise for each day is different. So, pick your favorite random event, and answer the following questions

Why do you think it is random or where the randomness comes from?

What is the sample space? Continues or discrete? Any range of the possible valus?

What distribution do you think is a good candidate to describe this event?

Sampling from an arbitrary Gaussian distribution. (3 points) In this problem, please write a simple code about sampling from a Gaussian distribution with pre-defined covariance matrices:

Case I: Σ = I

Case II: Σ is a diagonal matrix. You can define your own diagonal matrix, as long as it is a valid covariance matrix.

Your submission about this question should include

the code with name [ComputingID]-sample gaussian.py or [ComputingID]-sample gaussian.ipynb

the 2-D plots with 500 random samples from each distribution

[Hint: make sure the second parameter of multivariate normal is a valid covariance matrix.]

Conditional probability and independence. (4 points) Consider the two random variable X and Y with the following joint distribution

P(X,Y) X=0 X=1 X=2

Y

= 0

0.1

0.1

0.1

Y

= 1

0.25

0.3

0.15

What is the conditional probability of P (X | Y = 0)?

Are X and Y independent from each other? Why?
