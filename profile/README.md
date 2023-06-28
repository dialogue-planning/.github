# Dialogue Planning

## What is Dialogue Planning?
Dialogue planning is a subset of task-oriented dialogue agent development that uses automated planning to generate dialogue graphs for navigating conversations. The declarative nature of planning creates dialogue agents that are both flexible and verifiable.

[A Review of Plan‑Based Approaches for Dialogue Management](https://link.springer.com/article/10.1007/s12559-022-09996-0#Bib1) is a fairly recent SLR (systematic literature review) that covers the current work in the space.

##  Our Mission
Despite the 40+ papers in the space, dialogue planning is not widely adopted as the community is missing an accessible and maintainable system for dialogue planning development. We aim to flourish into a centralized hub for creating dialogue planning agents.  

![Current Architecture](./profile/architecture.PNG)

The basis of our system are `plan4dial` and `contingent-plan-executor`. `plan4dial` takes specification information to build and train and the dialogue agent, and `contingent-plan-executor` (extended from work at IBM) is the dialogue manager used to execute the conversation. We have also built upon this foundation to enhance the development process, resulting in tools at every step of development:  

- **Conception:** Use `automatic-entity-extraction` to generate potential entities to extract.
- **Creation**: Use `plan4dial` to specify the agent and determine how entities should be extracted.
- **Testing:** Use `conversation-alignment` to assess your agent's capabilities against conversation corpora.  
- **Deployment:** Run your agent with a Dockerized setup and deploy it to your website with our embeddable web UI, `widget`.  

More projects are to come as we continue to streamline and advance dialogue planning development.

🤖 Happy chatting! 🤖
