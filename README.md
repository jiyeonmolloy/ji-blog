# Ji Blog! 🐰

## June 2024
## 📚 Recommended Books for Software Engineers 📚

As a software engineer, continually enhancing your skills and knowledge is crucial. Reading books that provide insights into different aspects of software development, team dynamics, and coding best practices can significantly help contribute to your professional growth. 

Here are three highly recommended books that every software engineer should read.

## [Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations](https://www.goodreads.com/book/show/35747076-accelerate) 🚀

**Authors:** Nicole Forsgren, Jez Humble, Gene Kim

**Description:** "Accelerate" presents a data-driven approach to understanding what makes high-performing technology organisations excel. The book is based on the findings from the State of DevOps Reports and provides actionable insights into improving software delivery performance. It covers topics such as continuous delivery, lean management, and technical practices that drive success. 

- **Deployment Frequency**: How often an organisation successfully releases to production
- **Lead Time for Changes**: The amount of time it takes a commit to get into production
- **Change Failure Rate**: The percentage of changes that result in a failure in production
- **Time to Restore Service**: How long it takes to recover from a failure in production

## [Team Topologies: Organising Business and Technology Teams for Fast Flow](https://www.goodreads.com/book/show/44135420-team-topologies) 🤝

**Authors:** Matthew Skelton, Manuel Pais

**Description:** "Team Topologies" introduces a approach to designing and evolving organisational teams for optimal flow. The authors emphasise the importance of team interactions and provide practical advice on structuring teams to improve software delivery. The book discusses four fundamental team types and three team interaction modes, helping you create a more effective and responsive organisation.

- **Stream-aligned Team**: A team aligned to a flow of work from a segment of the business domain, taking end-to-end responsibility
- **Enabling Team**: A team that helps a stream-aligned team to overcome obstacles and gaps in capabilities
- **Complicated-Subsystem Team**: A team that deals with areas that require specialised knowledge and expertise
- **Platform Team**: A team that provides internal services to other teams to reduce their cognitive load


## [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.goodreads.com/book/show/3735293-clean-code) ✨

**Author:** Robert C. Martin

**Description:** "Clean Code" is a classic book that emphasises the importance of writing clean, maintainable, and efficient code. Robert C. Martin, also known as "Uncle Bob!" provides a guide to writing high-quality code that is easy to read and understand. The book is filled with practical examples and best practices, making it an essential resource for engineers at any level.

Happy reading! 📖😊


## May 2024
## Serverless Days!

Click [here](https://anz.serverlessdays.io/auckland/) to see the full agenda

I had the amazing opportunity to attend ServerLess Days. If you are working with serverless technology and would like to meet other active developers and technical leaders from across the Australia & New Zealand region, while hearing from some world-class speakers, I highly recommend attending this event!

Here is a quick recap of my learnings!!


### Think, Architect, and Build Serverless Applications as Set Pieces 
#### Speaker: [Sheen Brisals](https://anz.serverlessdays.io/speakers/sheen/)

- Accumulated architecture HIDES complexity
- Distributed architecture SHOWS the complexity
- Problem Decomposition 
    - Utilise serverless characteristics
        - Event-driven architecture
        - Using managed services
        - Infrastructure-as-code ♥
    - Employ PROVEN patterns
        - [Domain Driven Design](https://martinfowler.com/bliki/DomainDrivenDesign.html)
            - Domains and sub-domains
            - [Bounded context](https://martinfowler.com/bliki/BoundedContext.html)
        - [Team Topologies](https://teamtopologies.com/)
            - Team ownership and custodians
        - Microservices
            - Independently releasable single-purpose services
    - SUSTAIN the architecture, application and processes 🌳
        - ⬇ sustainability: Waterfall development
        - ⬆ sustainability: 
            - Serverless ways of thinking
            - Evolving architecture
            - Minimum Viable Product (MVP 🌟)
            - Modular, extendable and observable product
        - Follow lean principles
        - Improve Value Stream
        - Agile & Pragmatic
        - Start SMALL and scale!
        - Evolve in ITERATIONS
        - Automate EVERYTHING 😎
        - DevOps Mindset
        - Refactor Continuously 💖
- Growing talent in the team 🌻
    - Enablement within the team 🌼
    - Celebrating wins
    - Instill ownership

###  Whether Serverless or Not, It's all about how you drive your project! 
#### Speaker: [Nelly Sattari](https://anz.serverlessdays.io/speakers/nelly/)
- Keywords: Accountable, Agile, Healthy and Focused
- The art of impossible
    - Coach - Helping individuals
    - Connector - Building a healthy team
    - Conductor - Driving projects
    - Compass - Setting the direction
- Don't forget to connect with stakeholders
- [Atlas](https://www.atlassian.com/software/atlas) Atlassian product that is a teamwork directory. For example, every Monday we can review how the team is doing!
- Making it clear what everyone's roles and responsibilities are
- Building an Agile Team
    - Fixed: People, Team and Scope
    - Epic ▶ Milestone
        - Incremental delivery
        - Breakdown MVP
        - Carry out within 1 to 2 sprints
    - Importance of Sprint Goals ⚽
        - Achieving Sprint Goals is MORE important than shipping all the tickets
        - Each milestone could be a goal?
        - Goal setting meeting to review if the team met their goals in the previous sprint
            - Teams can answer YES, PARTIALLY or NO
            - If the sprint goal hasn't been met, have a meeting to identify why the goals were not met
            - Other Agile Rituals include Sprint Checkpoint and Capacity Planning
- 💟 DATA DRIVEN LEADERS 💟
    - Identifying work that is carried over multiple sprints, what are the dependencies? Why was this work not completed within the sprint?
    - Measuring velocity
    - Measure everything, no "gut feelings"
- Connection
    - Social events
    - Celebrating milestones
    - Recognition
    - Beware of burn-outs!
- Collaboration
    - Providing training
    - Mentoring and pairing
- Data-Driven Engineer who recognises importance of Agile rituals
- More team members can cause overhead
    - Adding more team members doesn't mean the team will have higher velocity
- Developing self-healing / stateless / idempotent systems
- Working on serverless and real time observability
- Summary
    - Do the simple thing first
    - Small team with fast feedback loop - showcase often
    - Identify risk early, shift-left and spike
    - Continuously measure performance and stress test
    - Isolate context boundaries (lambdas)
    - Solution must prove itself correct

###  Using serverless functions for real-time observability 
#### Speaker: [Liz Fong-Jones](https://anz.serverlessdays.io/speakers/liz/)
- Most realtime bulk workloads benefit
    - Move state from local machines onto object storage
    - Shard list of objects into work units
    - Parallelise object processing
    - Reduce results outside Lambda afterwards
- Beware the dragons! 🐉
    - Avoid latency-insensitive batch workloads (cost)
    - Avoid tiny workloads (set-up latency)
    - Check cloud provider limits, state your intentions (capacity planning)
    - Test cross-compilation including profiling to avoid performance issues with switchign architectures




