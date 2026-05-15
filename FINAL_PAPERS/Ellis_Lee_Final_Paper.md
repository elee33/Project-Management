## Final Paper: Open Workflow MVP
Ellis Lee, Spring 2026 IS 340-Project Management-Section A

PDF version: [ELLIS_LEE_FINAL_PAPER_OPEN_WORKFLOW_MVP.pdf](ELLIS_LEE_FINAL_PAPER_OPEN_WORKFLOW_MVP.pdf)

### Project Vision
The core idea behind the Open Workflow MVP is to transform disorganized, hard-to-manage problems into a clear, repeatable workflow. This project has both immediate and long-term objectives. In the short term, I aim to deliver a Minimum Viable Product (MVP) that includes essential features, thorough documentation, and a transparent system for version control. Looking further ahead, my goal is for this project to evolve into a lasting, "working open" resource. This means it should be easily reusable, adaptable through forking, and expandable, all while maintaining trust and clarity within the collaborative environment.

### The Collaboration Problem
Many teams face significant challenges when working together, leading to inefficiencies and frustration. These issues often stem from several key areas:

- Scattered Tools: Team members frequently struggle to keep track of tasks, decisions, and important files because they are spread across various platforms and applications. This fragmentation makes it difficult to maintain a unified project overview.
- Onboarding Friction: New collaborators often find it hard to quickly understand the current status of a project or how they can effectively contribute. The lack of a clear entry point or consolidated information slows down their integration into the team.
- Weak Institutional Memory: Meeting notes and critical decisions are often difficult to locate later, resulting in poor institutional memory. This can lead to repeated discussions, lost insights, and a general lack of historical context for ongoing work.
- Imbalanced Effort: Work distribution can become uneven because the ownership of tasks and project timelines are frequently unclear. This ambiguity can cause some team members to be overloaded while others are underutilized, impacting overall team morale and productivity.

### The Solution and Unique Value Proposition
#### The MVP Solution
The MVP provides a practical toolkit designed to streamline collaboration:

- A GitHub repository template that comes pre-configured with issues, milestones, and a Kanban board for task management.
- Ready-to-use templates for meeting notes, weekly status updates, and decision logs, ensuring consistent documentation.
- A clear contribution guide and an onboarding checklist to help newcomers get up to speed quickly and effectively.
- A script for generating weekly summaries directly from GitHub issues and pull requests, automating progress reporting.

#### Unique Value Proposition
My unique value proposition lies in offering a "plug and play," open-by-default workflow kit. This kit is specifically designed to transform messy, uncoordinated collaboration into a predictable and repeatable system, making it easier for teams to work together efficiently.

### Target Audience and Acquisition Channels
#### Target Audience
- Primary Audience: Student project teams and small remote research groups who often need structured collaboration tools.
- Early Adopters: Classmates in IS 340 and campus clubs that engage in project-based work.
- Secondary Audience: Newcomers to open-source projects who are looking for a more structured and guided way to contribute.

#### Growth Channels
- Leveraging the GitHub template repository itself and providing a clear README demonstration to showcase its utility.
- Using course announcements, peer sharing, and campus Discord or Slack channels to spread awareness.
- Actively using GitHub issues, discussions, and "first issue" labels to attract and guide potential contributors.

### Execution, Timeline, and Metrics
#### 5-Week Resource Plan (8 to 10 hours per week)
- Project lead: 2 hours per week
- Developer: 4 to 5 hours per week
- Documentation and design: 2 hours per week
- User testing: 1 hour per week

#### Milestones
- Week 1: Establish the repository skeleton, define labels, set up the project board, and create the initial contribution guide.
- Week 2: Develop templates for meeting notes, decision logs, and status updates, completing the MVP.
- Week 3: Implement the summary script and basic Continuous Integration checks.
- Week 4: Conduct pilot testing with users to identify and fix friction points.
- Week 5: Refine and polish the project, release version 1.0, and complete the final write-up.

#### Success Metrics
- New users completing their first task within 1 day of onboarding.
- A high turnaround rate for pull requests.
- Meeting notes being posted within 24 hours of meetings.
- High satisfaction scores from users and contributors.

### Agile Workflow (MERN Stack)
My development process uses an Agile workflow tailored for the MERN stack: MongoDB, Express.js, React, and Node.js.

- Sprint 0 (Project Initiation): Establish the technical foundation by setting up the MERN scaffolding, configuring ESLint and Prettier, and organizing the repository.
- Active Sprints (2-Week Cycles): Operate in two-week sprints with an 80/20 split between new feature development and refactoring technical debt.
- Code Review Gateway (Daily): Use daily linting checks and documentation validation as a quality control checkpoint.
- Long-Term Scaling (1 to 5 Years): Plan for bi-annual audits, regular version upgrades, and database scalability reviews to prevent architectural and security issues.

### Technical Debt Management
#### Initial Debt
Choosing the MERN stack intentionally incurs some technical debt in exchange for development speed. MongoDB offers flexibility but lacks a strict schema, and React allows for rapid component building that can sometimes lead to less organized code.

#### Short-Term Mitigation
I employ a "fix forward" strategy to mitigate short-term debt. Strict linting rules and a dedicated 20% of sprint time for refactoring help address code quality issues proactively before they accumulate.

#### 5-Year Outlook
Over a five-year horizon, I anticipate several challenges related to technical debt:

- Migration Costs: There will be a continuous need to update React and Node.js to prevent security vulnerabilities and keep pace with ecosystem changes.
- Scalability: MongoDB may encounter limitations if the project evolves to require more complex data relationships than initially anticipated.
- Organizational Debt: Early architectural shortcuts and decisions must be documented so future team members can understand past choices and maintain continuity.

### The Double-Edged Sword of Automation
Automation is powerful, but it must be applied thoughtfully because its impact varies across different project scales.

- Small-Scale Projects (3 to 5 Contributors): Automation scripts can help maintain momentum, but complex configurations can consume too much of a short 5-week timeline and create more friction than value.
- Open-Source Communities: Bots and automated tools can reduce the burden on maintainers by assisting with issue triage and Continuous Integration checks. However, overly sterile or automated rejections can alienate newcomers and weaken the mentorship that helps communities grow.
- Large-Scale Programs: Dashboards and automated reporting can centralize data across many teams, but they can also create "watermelon project" reporting, where everything appears green on the surface while serious problems remain underneath. This happens when automation strips away the qualitative context needed to understand team performance and project health.

### References
[1] Hussein, B. (2021). Addressing Collaboration Challenges in Project-Based Learning: The Student's Perspective. *Education Sciences, 11*(8), 434. https://doi.org/10.3390/educsci11080434

[2] Drofa, D. (2025). Optimization of software development processes through the use of full-stack technologies and automation. *Contemporary Issues in Artificial Intelligence, 1*. https://doi.org/10.69635/ciai.2025.12

[3] Assessment of automation and integration technology's impacts on project stakeholder success. *Automation in Construction, 16*(1), 1-13. https://doi.org/10.1016/j.autcon.2006.01.001
