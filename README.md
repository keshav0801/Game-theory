# Three-Sided Matching: A Game Theory Approach

## Overview

The `three sided matching.ipynb` notebook explores a **game theory problem** involving a matching scenario where three distinct groups need to be paired simultaneously. This extends traditional two-sided matching algorithms, such as Gale-Shapley's stable marriage problem, into a more complex setting, creating challenges in ensuring stability and fairness among the three groups.

## The Problem

In a **three-sided matching problem**, there are three distinct sets of participants (e.g., employers, candidates, and training institutes). Each participant group has preferences over the other two groups. The objective is to:

1. Form optimal matches between participants from the three sets.
2. Ensure **stability**, such that no subset of participants prefers an alternative matching over the current one.
3. Address challenges such as conflicting preferences and trade-offs across groups.

## The Algorithm

This notebook demonstrates an algorithm designed to tackle the complexities of three-sided matching, including:

- **Preference modeling**: Representing the preferences of each participant group in an effective manner.
- **Iterative matching**: Developing a stable matching through iterative proposals and adjustments.
- **Game-theoretic insights**: Leveraging concepts like Nash equilibrium and Pareto efficiency to optimize matches.

## Applications

This algorithm has wide-ranging applications, including but not limited to:

- **Job Market Allocations**: Matching employers, candidates, and skill-development institutes.
- **Supply Chain Optimization**: Coordinating suppliers, manufacturers, and distributors.
- **Resource Allocation**: Addressing multi-party negotiations in markets or collaborative environments.

## How This Algorithm Helps

The algorithm provides a systematic and computationally efficient approach to solving complex multi-sided matching problems. By balancing preferences and incorporating stability principles, it ensures that:

- No participant group feels dissatisfied with the outcome.
- The solution is robust and minimizes disruptions arising from preference conflicts.
