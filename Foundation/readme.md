<!--
This file is auto-generated from a 'template.md'
file using the 'md-process' script.
Therefore *DO NOT* edit this file directly!
Instead edit the template file and then run 'md-process'.
-->

# SDLC

## Table of Contents

* [What is Software Development Life Cycle?](#what-is-software-development-life-cycle?)
* [What is the goal of SDLC?](#what-is-the-goal-of-sdlc?)
* [The Software Triangle](#the-software-triangle)
  * [The Iron Pyramid?](#the-iron-pyramid?)
* [Managing Risk](#managing-risk)
* [Traditional Approach - Waterfall](#traditional-approach---waterfall)
* [Why is Waterfall so Attractive?](#why-is-waterfall-so-attractive?)
* [Enter Agile](#enter-agile)
* [For Further Reading](#for-further-reading)


## What is Software Development Life Cycle?


> _SDLC_ is term referring to a process or set of processes for planning, creating, testing, and deploying an software product (i.e. a library, framework, application, website, etc.)

![SDLC](images/sdlc.png)

---

## What is the goal of SDLC?

* **Quality**: Ensuring that a high-quality product is built and delivered
* **Scope**: Delivering the _correct_ product
* **Cost**: Estimating and controlling cost

## The Software Triangle
![Software Triangle](images/iron-triangle.jpg)

### The Iron Pyramid?

![Software Triangle](images/time-cost-quality-scope.jpg)

Or simply:

![Software Triangle](images/fast-good-cheap.png)

BOTTOM LINE: You get to pick 2 out of 3
## Traditional Approach - Waterfall

![Waterfall Process](images/waterfall.png)

Waterfall follows a very *familiar* approach to designing and building a system:

* Figure out what you want
* Design it
* Build it
* Test it
* Ship it
* Enjoy

But *waterfall* is not usually a good fit for large *Software* projects, because certain *assumptions* do not hold.

Waterfall _assumes_ that we know everything we need to know at the beginning of the project:

* What features are needed
* What technologies are a good fit
* How long it will take
* How many developers we need

Waterfall attempts to answer these questions and _lock them down_ near the beginning of the project. 
The reason that these assumptions don't hold for most Software Development projects is because the software industry is *highly volatile*.

* Markets change
* Technologies change
* What seemed like a good idea 3 months ago seems silly or irrelevant now.

We need a process for building software that can *ADAPT* quickly to change!

## Why is Waterfall so Attractive?

Waterfall is attractive because:

* It is familiar - it is how we generally approach big projects
* It is logical, intuitive, and sequential
* It is easy to work when budgeting a project and dealing with legal / contract matters
* It gives the _illusion_ of managing and minimizing risk


## Enter Agile


Agile accepts the fact that everything continues to change at a rapid rate:

* Markets change
* Technology changes
* Culture changes
* Business dynamics change
* Our understanding continues to evolve

> So we must be *agile* in our approach to developing a software solution to a problem.

**The four core values outlined in the Agile Manifesto are:**

_Individual interactions are more important than processes and tools_ 
People drive the development process and respond to business needs. They are the most important part of development and should be valued above processes and tools.

_A focus on working software rather than thorough documentation_
Before Agile, a large amount of time was spent on documenting the product throughout development for delivery. The list of documented requirements was lengthy and would cause long delays in the development process. While Agile does not eliminate the use of documentation, it streamlines it in a way that provides the developer with only the information that is needed to do the work

_Collaboration instead of contract negotiations_ 
Agile focuses on collaboration between the customer and project manager, rather than negotiations between the two, to work out the details of delivery. Collaborating with the customer means that they are included throughout the entire development process, not just at the beginning and end, thus making it easier for teams to meet the needs of their customers. For example, in Agile software development, the customer may be included at different intervals for demos of the product. However, the customer could also be present and interacting with the teams on a daily basis, attending all meetings and ensuring the product meets their desires.

_A focus on responding to change_ 
Traditional software development used to avoid change because it was considered an undesired expense. Agile eliminates this idea. The short iterations in the Agile cycle allow changes to easily be made, helping the team modify the process to best fit their needs rather than the other way around. Overall, Agile software development believes change is always a way to improve the project and provide additional value.

**Agile Manifesto**

1. The highest priority is to satisfy the customer through early and continuous delivery of valuable software.

2. The project team welcomes changing requirements, even late in development. Agile processes harness change for the customer’s competitive advantage.

3. Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.

4. Business people and developers must work together daily throughout the project.

5. The process builds projects around motivated individuals, giving them the environment and support they need, and trusts them to get the job done.

6. A face-to-face conversation is the most efficient and effective method of conveying information to and within a development team.

7. Working software is the most important measure of progress.

8. Agile processes promote sustainable development. The sponsors, developers, and users should maintain a constant pace indefinitely.

9. Pay continuous attention to technical excellence, and good design enhances agility.

10. Simplicity is essential. This is the art of maximizing the amount of work not done.

11. Self-organizing teams produce the best architectures, requirements, and designs.

12. At regular intervals, the team reflects on how to become more effective and adjusts its behavior accordingly.


**Scrum and kanban**

Scrum and kanban are the primary agile processes.

Important items to understand:

The Scrum Team consists of three roles, namely a ScrumMaster, a Product Owner, and the Team.

ScrumMaster
The ScrumMaster (sometimes written as the Scrum Master, although the official term has no space after “Scrum”) is the keeper of the scrum process. He/she is responsible for-

making the process run smoothly
removing obstacles that impact productivity
organizing and facilitating the critical meetings
Product Owner
The Product Owner is responsible for maximizing the value of the product and the work of the Team. How this is done may vary widely across organizations, Scrum Teams, and individuals.

The Product Owner is the sole person responsible for managing the Product Backlog. Product Backlog management includes-

Expressing Product Backlog items clearly.

Ordering the Product Backlog items to best achieve goals and missions.

Optimizing the value of the work the Team performs.

Ensuring that the Product Backlog is visible, transparent, and clear to all, and shows what the Team will work on further.

Ensuring that the Team understands items in the Product Backlog to the level needed.

The Product Owner may do the above work, or have the Team do it. However, the Product Owner remains accountable for these tasks.

The Product Owner is one person, not a committee. The Product Owner may represent the desires of a committee in the Product Backlog, but those wanting to change a Product Backlog item’s priority must address the Product Owner.

For the Product Owner to succeed, the entire organization must respect his or her decisions. The Product Owner’s decisions are visible in the content and ordering of the Product Backlog. No one is allowed to tell the Team to work from a different set of requirements, and the Team is not allowed to act on what anyone else says. This is ensured by ScrumMaster.

The Team
The Team is self-organizing and cross-functional. That means the team comprises of analysts, designers, developers, testers, etc. as appropriate and as relevant to the project.

Some people in the industry refer to this team as development team. However, such a reference is leading to controversy that the team can have only developers and no other roles. It is an obvious understanding that it is only a misconception. To develop a software product, we require all the roles and that is the essence of scrum – the team will function in collaboration. Cross-functional teams have all competencies needed to accomplish the work without depending on others not part of the team, and thus time and effort can be saved. The team model in Scrum is designed to optimize flexibility, creativity, and productivity.

Optimal Team size is small enough to remain nimble and large enough to complete significant work within a Sprint. The Team size should be kept in the range from five to nine people, if possible. Fewer than five team members decrease interaction and results in smaller productivity gains. Having more than nine members requires too much coordination.

The scrum team works together closely, on a daily basis, to ensure the smooth flow of information and the quick resolution of issues. The scrum team delivers product iteratively and incrementally, maximizing opportunities for feedback. Incremental deliveries of a complete product ensure a potentially useful version of working product is always available.


Some organizations start with kanban because it’s relatively easy to explain and implement. Kanban works as a fan-in and fan-out process where the team pulls user stories from an intake board and funnels them through a workflow until they are marked done.

But many organizations implement scrum, which organizes the work in cadences called sprints, usually lasting one or two weeks. The product owner writes the requirements as user stories, then prioritizes them in a backlog based on their business value. The team reviews the backlog and commits to the top user stories they can complete during the sprint.

Scrum includes several standard meetings (sometimes called scrum ceremonies or scrum rituals) to help teams commit to sprint priorities, complete the work during the sprint, and end each sprint successfully. These meetings usually include a few common elements:

* Sprint planning is where the product owner shares priorities, and the team decides how much work it can complete during the sprint. 
* Daily standup meetings help teams discuss the status of user stories; teammates share their daily goals, and anyone can escalate blocks that impede the team’s progress.
* Sprint reviews are demo meetings at the end of the sprint, where the functionality is shown to the product owner to gain acceptance on completed work.
* Retrospective meetings are where the team discusses what went well and what needs improvement in their agile and software development processes.

---

![Scrum Process](images/scrum-big.png)

---

## For Further Reading

* [DZone RefCard on Scrum](dzone-rc-scrum.pdf)

