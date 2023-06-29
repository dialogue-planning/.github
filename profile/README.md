# Dialogue Planning

## What is Dialogue Planning?
Dialogue planning is a subset of task-oriented dialogue agent development that uses automated planning to generate dialogue graphs for navigating conversations. The declarative nature of planning creates dialogue agents that are both flexible and verifiable.

[A Review of Plan‑Based Approaches for Dialogue Management](https://link.springer.com/article/10.1007/s12559-022-09996-0) is a fairly recent SLR (systematic literature review) that covers the current work in the space.

##  Our Mission
Despite the 40+ papers in the space, dialogue planning is not widely adopted as the community is missing an accessible and maintainable system for dialogue planning development. Our goal is that `dialogue-planning` will flourish into a hub for dialogue planning research and development.  

![Current Architecture](./profile/architecture.PNG)

The basis of our system are [plan4dial](https://github.com/dialogue-planning/plan4dial) and [contingent-plan-executor](https://github.com/dialogue-planning/contingent-plan-executor). [plan4dial](https://github.com/dialogue-planning/plan4dial) takes specification information to build and train and the dialogue agent, and [contingent-plan-executor](https://github.com/dialogue-planning/contingent-plan-executor) (extended from work at IBM) is the dialogue manager used to execute the conversation. We have also built upon this foundation to enhance the development process, resulting in tools at every step of development:  

- **Conception:** Use [automatic-entity-extraction](https://github.com/dialogue-planning/automatic-entity-extraction) to generate potential entities to extract (coming soon).
- **Creation**: Use [plan4dial](https://github.com/dialogue-planning/plan4dial) to specify the agent and determine how entities should be extracted.
- **Testing:** Use [conversation-alignment](https://github.com/dialogue-planning/conversation-alignment) to assess your agent's capabilities against conversation corpora (coming soon).  
- **Deployment:** Run your agent with a Dockerized setup and deploy it to your website with our embeddable web UI, [widget](https://github.com/dialogue-planning/widget).  

More projects are to come as we continue to streamline and advance dialogue planning development.

## Join Us
We welcome suggestions and contributions to `dialogue-planning`! Feel free to use the [discussions](https://github.com/orgs/dialogue-planning/discussions) tab to share your suggestions and ideas.

🤖 Happy chatting! 🤖
