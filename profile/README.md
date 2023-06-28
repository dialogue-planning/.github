# Dialogue Planning

## What is Dialogue Planning?
Dialogue planning is a subset of task-oriented dialogue agent development that uses automated planning to generate dialogue graphs for navigating conversations. The declarative nature of planning creates dialogue agents that are both flexible and verifiable.

[A Review of Plan‑Based Approaches for Dialogue Management](https://link.springer.com/article/10.1007/s12559-022-09996-0#Bib1) is a fairly recent SLR (systematic literature review) that covers the current work in the space.

##  Our Mission
Despite the 40+ papers in the space, dialogue planning is not widely adopted as the community is missing an accessible and maintainable system for dialogue planning development. We aim to flourish into a centralized hub for creating dialogue planning agents from conception to testing to deployment.  

The basis of our system are `plan4dial` and `contingent-plan-executor`. `plan4dial` takes specification information to build and train and the dialogue agent, and `contingent-plan-executor` (extended from work at IBM) is the dialogue manager used to execute the conversation.
