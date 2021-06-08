

# Introduction to the course and each other

 - This is a class that aims to help you reason about the design and analysis
   of randomized field experiments. Turns out that the main tool for this
   reasoning is statitics. So, this is a class that has a lot of statistics in
   it.

 - We are too many for long introductions. I suspect that most of you know each other already.
I hope we will get to know each other more as the week goes on.

  - Some chances to talk in small groups each day. <https://docs.google.com/spreadsheets/d/1uQH8Nl0LAL2MNd_itv0Xh-VqO8jCHGaR3Vn7sKTuumY/edit?usp=sharing>

 - Office hours next week via our secret link. 

 - I'll try to maintain a collaborative online document of class questions and answers at <https://hackmd.io/@JakeB/EUI-Class-1/edit>

 - Who am I? 

 - How might we have a useful week on Zoom?
   - Limit my presentations.
   - Breaks.
   - Lots of interruptions and questions from you all. (Particularly useful if you do some reading **before** class.)
   - Time to work on your own where I (and others) in the class are available.
 
# Plan for the Course So Far

 - The Syllabus
  - A lot of statistics
  - Fun with R

 - Idea is for you to be able to fill out the [EGAP Research Design Form](https://egap.github.io/theory_and_practice_of_field_experiments/the-research-design-process.html) (at least in part) by the end of the week.

# Goal for the day

  - Talk about experiments in general. What have you arrived at this course thinking about them? How might they relate to social science more generally? 
  - Talk about causal inference and especially counterfactual causal inference and the idea of potential outcomes. These are building blocks for the statistics later in the week (i.e. tomorrow).
  - Talk about randomization and, I hope, practice how to produce columns of random numbers.

# Your thoughts about experiments so far

 - Benefits/Advantages: <https://www.menti.com/2r6ckzs365>
 - Costs/Disadvantages: <https://www.menti.com/zopwk3hfew>

# Randomized Experiments in Context:

 The point of most social and behavioral science experimental research design
 is to learn about theory not about the world per se.

(some slides)

# Your Research Interests:

<https://www.menti.com/xwbfd6iwqf>


## Questions so far?

 - Why experiment? Why randomize?
 - Why not randomize?

# Counterfactual Causal Inference

 - Why would a social scientist manipulate an intervention so that some people
   or groups of people receive it and others do not? When might we \emph{not}
   want to experiment?  What are common approaches to preventing harm to
   experimental subjects?
 - What does "X causes Y" mean in the counterfactual causal framework? What is
   a "potential outcome"? How might learning about counterfactual causal
   relationships help us understand our theories better? 

# Randomization

 - Why might we use randomization to learn about counterfactual causal
   relationships?

 - When we do not randomize what questions arise that do not arise if we do randomize?

 - What new questions must we answer if we do randomize?

- How to use R to randomly assign units in different types of randomized
   designs: simple, complete, blocked, clustered.

# Your turn:

 - Start work on the research design form. <https://egap.github.io/theory_and_practice_of_field_experiments/the-research-design-process.html#design-form-and-pre-registration>

 - What will you randomize and how? What will you learn from this randomization
   plan?
 - Produce a replicable randomization of this type as an exercise. (Probably
   using the `randomizr` package for R).


