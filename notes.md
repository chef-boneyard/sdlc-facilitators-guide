# Principles
[Agile Principles](http://agilemanifesto.org/principles.html)



1. Our highest priority is to satisfy the customer through early and continuous delivery of valuable software.

1. Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage.
 
1. Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.
 
1. Business people and developers must work together daily throughout the project.
 
1. Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
 
1. The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.
 
1. Working software is the primary measure of progress.
 
1. Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.
 
1. Continuous attention to technical excellence and good design enhances agility.
 
1. Simplicity--the art of maximizing the amount of work not done--is essential.
 
1. The best architectures, requirements, and designs emerge from self-organizing teams.
 
1. At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

[XP Values](http://www.extremeprogramming.org/)

+ Communication
+ Simplicity
+ Feedback
+ Respect
+ Courage

[XP Rules](http://www.extremeprogramming.org/rules.html)

##Lean Kanban Software Development
[Kanban](http://leankit.com/kanban/what-is-kanban/)

+ Visualize workflow
+ Limit Work in Process (WIP)
+ Manage Flow
+ Make process policies explicit
+ Improve collaboratively

[Lean Principles](https://en.wikipedia.org/wiki/Lean_software_development)

+ Eliminate waste
+ Amplify learning
+ Decide as late as possible
+ Deliver as fast as possible
+ Empower the team
+ Build quality in
+ See the whole

## Chef Engineering Mission and Beliefs

Our Mission - Write the software that will define how an entire generation of businesses deliver technology to their customers

Our Beliefs - Our beliefs in what makes a great software organization starts from a reflection on the This - the things that we believe make us a great company, period:
+ Fuel the love of Chef
+ Make it easy to be successful with Chef
+ Give organizations a reason to buy
+ Be their favorite team to work with
+ Speed matters, be disruptive
+ We build software for our users - we do what is right for them
+ We believe in flexibility
+ We are allergic to things that are slow
+ We work together to make better, faster decisions, and we learn from our mistakes
+ We hire and work with the best (great people have a shot at great software, which gives you a shot at a great company)
+ We continuously develop, build, test, and deploy our software
+ We believe CI failures are a big deal, and returning builds to a passing state is a first priority
+ We are transparent internally and externally
+ We take security seriously
+ We work small so we can win fast, fail small, and learn continuously
+ Chef would exist without the company; but Chef.io would not exist without the community
+ We value diversity of perspective, backgrounds, geography and experience
+ We embrace a healthy lifestyle
+ We value each other as people, we value each other as a team
+ Vulnerability is the other side of trust
+ We respect the sacrifices we make on behalf of our users and each other (DW heroic behavior should not be required)
+ We are clear about risks, rewards, and trade-offs
+ When we make decisions that end up with wrong outcomes, we learn from it and improve our judgement
+ We plan in advance for emergent contingencies (DW: we allow changes to plans based on emergent items?)
+ We celebrate each other’s successes, and recognize and encourage each other
+ We believe in bacon
+ We disagree and commit
+ We feel pain when our product has obstacles for our users
+ We don’t stop believing and hold on to that feeling.


[Chef SDLC](https://docs.google.com/document/d/1qNWJspr4UQ0ugM9cAbiHmeeKOMwMoYbgX1zSY7E7Pw0/edit#heading=h.aw3pkr34ru3v)

## Team

SDLC: Great teams build great Products which make great Companies
We build software for our users - we do what is right for them
We work together to make better, faster decisions, and we learn from our mistakes
We continuously develop, build, test, and deploy our software
Form cross functional team; collaborate with each other; have a high degree of internal alignment; empower each other to get the work done.

Feature teams are comprised of a Product Engineer, Lead Engineer, Product Designer, Software Engineers. Whole team collaborates on Epics and Features.
+ Product Engineer responsible for building a thing customers need, producing Epics and Features
+ Lead Engineer responsible for shipping and architectural supervision (DW: advice, support, mentoring?)
+ Product Designer design how customers interact with the product
+ Software Engineer responsible for [design, creation, testing] quality of results
How does a group become a team? What does starting look like?

Charter/Mission
Working Agreement/ Definition of Done
Team Name
Ceremonies - Standup, Demo, Retrospective
Team size
Roles
+ Product Engineer - responsible for building a thing customers need, producing Epics and Features
+ Lead Engineer - responsible for shipping and architectural supervision (DW: advice, support, mentoring?)
+ Product Designer - design how customers interact with the product
+ Software Engineer - responsible for [design, creation, testing] quality of results

Tools for reaching agreements and dealing with conflict
+ Disagree and commit
[Fist of Five](http://freechild.org/Firestarter/Fist2Five.htm)
Getting to Yes - [Perfection Game](http://liveingreatness.com/core-protocols/perfection-game/)
But stop lying to each other (fake agreement)

Ceremonies and cadence
Little’s law
Estimation or flow?
Cycles – 2 weeks
Meetings
Standup
Daily
<=15 minutes
Address Expedited Issues
Address anything that is blocking you in completing tasks
For Fixed Delivery work, are we on track or need to communicate slip
Review stuck (aka Blocked) issues
Discuss work that is being done but not on board (DW: minimize towards zero)
Queue Replenishment (aka Refinement)
Weekly
30 minutes
Ensure just enough work is ready for team
Review items In Analysis, answer outstand questions from team. Sort
Review Ready for Analysis. Sort
Refine work [at the top of ] the Backlog, ensuring there is enough work in Ready for Analysis before the next Replenishment meeting
Demo
Weekly
30 minutes
Demonstrate features shipped that week.
Only show work deployed to an acceptance environment
Retrospective
Monthly
45 minutes
Connect as a team to discuss process and outcomes
Gather information to identify
What went well?
What were challenges?
What [few] experiments could we try to improve our process, flow, and results?
Health Check (across teams)
Monthly
45 minutes
For Engineering Leadership, Engineering Leads, Product Engineers, and Employee Experience folks
Each Feature team ranks their health (RYG)
Ask the Red teams to describe their issues, providing suggestions and scheduling follow-up with Leadership
Ask the Yellow teams to describe their issues, providing suggestions and feedback.
Sustainable pace
From Agile Principles “Agile processes promote sustainable development [everyone] should be able to maintain a constant pace indefinitely.”
Overtime causes negative productivity. http://cs.stanford.edu/people/eroberts/cs181/projects/crunchmode/econ-crunch-mode.html
How we work
Work Breakdown
Themes are tracked in the THEME project, high level and strategic
Epics are tracked in the ROAD project, provide customer facing functionality, grouped by Theme
Features are one piece of functionality needed to complete an Epic. They are tied to an Epic and are customer facing. Individual feature teams have their own unique project, where they track their Features, Chores, and Bugs
Optionally, there may be a project created for a given product - these are placeholders for universal Bugs or Chores waiting to be assigned to a feature team. They never contain Features.
Chores are work to keep our own house in order: maintenance, refactoring, process improvements
Bugs - issues where we thought the system should work one way, and it doesn’t.
Jira
Jira used for development of Themes and Epics, and tracking features, chores, and bugs.
Kanban Boards - each column must have a WIP limit
In Backlog
Ready for Analysis
In Analysis
In Development
Ready for Acceptance
In Acceptance
Ready to Deliver
Classes of Service
Expedite (Jira Priority = Highest) mean items that must be worked on by the team first (DW other work is stopped until complete)
Fixed Delivery work is marked by setting the Due Date in Jira
Standard - all other work is considered standard and has equal weight.
Customer Interviews
Stories and Story Mapping
http://jpattonassociates.com/the-new-backlog/
Product
How we work with product team (see Work Breakdown)
Work discovered, abandoned
Triage, chores, bugs (see Work Breakdown)
Features (see Work Breakdown)
Practices/Craft - optional, not stated in SDLC
TDD/BDD
What is TDD http://guide.agilealliance.org/guide/tdd.html
Is TDD Dead - a Youtube discussion https://www.youtube.com/watch?v=z9quxZsLcfo
Pairing http://guide.agilealliance.org/guide/pairing.html
CI/CD
Refactoring
Coding conventions
Quality
What is tech debt
Ship it - I’m using Delivery
What does “done” look like?
Metrics: instrumentation
Continuous Delivery
DevOps at Chef
Evolving - How do teams evolve the SDLC process
Do it! Practice as stated
Socialize and learn
Change when appropriate
Other things:
Action != Progress
Cultural Debt >= Technical Debt
Get on the Bus
Practice not Prediction
Create explicit ties back to SDLC
