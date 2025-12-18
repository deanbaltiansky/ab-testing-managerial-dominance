# ab-testing-managerial-dominance
<<<<<<< HEAD

A/B test examining how relational expectations shape leaders’ communication choices
=======
A/B test examining how relationship expectations shape leaders’ communication choices

**Read the analysis report**
https://deanbaltiansky.github.io/ab-testing-managerial-dominance/
>>>>>>> e9d8d75163d49fefb6605cf27ed84e8c0bab335b

# Overview

This repository contains the design and analysis of a randomized A/B experiment testing whether leaders’ expectations about relationship consequences influence their likelihood of choosing a more dominant communication style.

Participants were randomly assigned to reflect on either the positive or negative relationship impact of a dominant message before making a real communication choice. The analysis shows that framing dominance as relationally beneficial—rather than harmful—causally increases leaders’ willingness to use dominant communication, even when financial incentives are held constant.

The repo demonstrates a clean, industry-relevant A/B testing workflow with a binary behavioral outcome, grounded in realistic managerial decision-making.

# Experimental design

Online participants (N = 492) were instructed to act as managers in a mid-sized company. They were told to assign a challenging task to an employee (another participant on the platform) whose performance affected both parties’ bonuses.

Before choosing how to communicate about the task, managers were randomly assigned to one of two conditions:

  1. Positive Relationship Impact Condition: Participants reflected on how the employee might react **positively** to a dominant message.
  2. Negative Relationship Impact Condition: Participants reflected on how the employee might react **negatively** to a dominant message.

All participants were then shown two possible messages they could send to the employee:

  1. a dominant communication option, and
  2. a non-dominant communication option.

The primary dependent variable was whether the manager selected the dominant message (0 = non-dominant, 1 = dominant).

# Validation and analysis approach

To verify that the manipulation worked as intended and to rule out alternative explanations, the analysis includes:

  - Treatment checks
    - Self-reported expected employee reactions
    Lexical sentiment analysis (AFINN) of open-ended reflections
    Word-count comparisons to ensure equivalent engagement across conditions
  - Primary outcome analysis
    - Difference-in-means and logistic regression (binary choice outcome)
    - Effect sizes reported as odds ratios and probability differences
  - Robustness checks
    - Controlling for expected task compliance to isolate relational framing effects

All analyses are fully reproducible and run directly from the de-identified dataset included in the repo.

# Why this matters

In organizations, leaders frequently face choices about how to communicate—not just what to decide. This project shows that subtle shifts in how leaders think about relational consequences can meaningfully change their behavior, independent of incentives.

From an analytics perspective, the repo illustrates how to:

  - design and analyze a clean A/B experiment,
  - validate manipulations using both survey and text data,
  - estimate and communicate causal effects in a business-relevant context.
  
# What this repo shows

  - Designing and analyzing a randomized A/B test
  - Working with binary behavioral outcomes
  - Validating experimental manipulations with text-based measures
  - Estimating treatment effects using logistic regression
  - Communicating results clearly and reproducibly for non-academic audiences

