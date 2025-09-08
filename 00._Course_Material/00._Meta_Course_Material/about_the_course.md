# About the course

[Kea Katalog](https://katalog.kea.dk/course/3050407/2025-2026)

---

## Terminology

**The semester repository**: This repository is where all the course material is. It will serve as the main repository for the semester.

**The simulation**: The simulation will simulate real-world web traffic to your website. 

**The project**: Throughout the semester you will work on a single project and this is also what you defend at the exam. Scale down your expectations significantly regarding implementing a search engine.

---

## Reading

There is only a bit of literature to read in this course. (It is likely to be brought up during the exam.)

There is a lot of course material and I expect everyone to read and understand it. Even if you are not the one to have implemented the task you should've at least thoroughly read and understood the assignment.

---

## Course workload

**Workload**: There is a steep work load in the beginning. It's supposed to become easier towards the end which should fit well with the idea of DevOps. You should create a lot of automation which allows you to lean back later on.  

**Complexity**: The topics are relatively simple in the beginning. Becomes more complex and difficult to implement later on. 

---

## Group work

Everyone must actively participate in the group work and commit. Prior to the exam we will run a script to investigate repository activity on a student basis.  

Use the fact that you work in groups to your advantage. Support each other. Share knowledge. 

I don't expect everyone to know exactly how something was implemented but I expect all group members to take shared responsibility for the project. This means that the exam will focus on **why** a choice was made, what advantages and disadvantages you predicted in advance and what you learned from it.

---

## [Whoknows variations](https://github.com/who-knows-inc/whoknows_variations)

For select few topics you will be provided step-by-step tutorials. 

Flask variations are optional in the sense that it is not required to attend the exam. However, I recommend that everyone tries to follow the tutorials for themselves, even if it isn't used in the exam project. They aim to teach you useful skills.

These tutorials are meant to be as simple as possible. There are better practices and more professional approaches. For the exam you will be evaluated on your knowledge on these practices, personal reflections and your group's implementation. 

Therefore, feel free to deviate from the tutorials if you found a better way. Your grade will reflect your level of ambition. The tutorials exist as a fallback so that no group gets left behind. 

---

## Assignments

Assignments aim to follow this structure:

```markdown
# [[Optional]] Assignment title

Summary / tagline

**Type**: Individual, Group work

**Soft Deadline/Hard Deadline/No Deadline**: 

[**Motivation**: Why you want to complete this task.]

[**Part of mandatory I/II**]
[**Part of the exam report**]


[## Requirement]
```

Square brackets indicate that the element is optional.

For the type:

- Individual: I want everyone to engage with the assignment alone and learn how to do it or learn from it.

- Group work: You are free to delegate the work, however, everyone is still expected to understand the assignment and how your group solved it.

---

## Lecture structure

A lecture day will typically consist of a presentation of a new topic with hands-on class work. 

By the end of it, you get the chance to ask questions. If you have questions then please write them down so you can remember to ask them during the designated Q+A.

Some days you might get some time to coordinate group work. 

---

## Course overall structure

This overview is to make you see the future milestones and know how to pace yourself throughout the course. I recommend starting simple, working in iterations and holding out on implementing the topics that come later. 

| Week | Topics                                            | Milestones (complete after the lecture)                       |
|------|---------------------------------------------------|---------------------------------------------------------------|
| 1    | Intro + Tools                                     | Understand the legacy code + system                           |
| 2    | REST API, OpenAPI, GitHub Actions                 | Start rewriting the project                                   |
| 3    | Cloud, Azure, Deployment                          | Deploy the project, prepare for the simulation trial          |
| 4    | Software Quality, Linting, CI                     | Ensure software quality, implement CI, fix simulation errors  |
| 5    | Docker, The Simulation                            | Begin Dockerization                                           |
| 6    | Docker-compose, CD, Agile, DevOps                 | Implement Continuous Delivery, reflect on DevOps              |
| 7    | Eficode (External lecturer)                 |                                                               |
| 8    | Continuous Deployment                             | Implement Continuous Deployment                               |
| 9    | Testing, Security                                 | Create tests, integrate security in pipelines, start using TLS|
| 10   | Databases, ORM, Data Scraping / Web Crawling      | Explore databases beyond SQLite, consider ORM, start scraping |
| 11   | Searching, Logging, Monitoring                    | Set up monitoring                                             |
| 12   | Infrastructure as Code (IaC)                      | Consider IaC                                                  |
| 13   | Deployment Strategies, Orchestration, Maintenance | Consider a deployment strategy, The simulation is taken down  |
| 14   | Report                                            |                                                               |
| 15   | Report + Exam Preparation                         |                                                               |


---

## Teams

#### Remember!!!! I really want the Teams room to be lively. If you make it nice to post in the channels, then you improve the overall course experience for yourselves.


Teams subchannels:

| Channel Name     | Explanation                                                                                                                                                    |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **General**      | Course material, lecture corrections, course information and anouncements.                                                                                                                                  |
| **Assignments**  | For the mandatories and handing in missed assignments.                                                                                                         |
| **Not_in_a_group** | For help with group formation, especially for students who are not present the first week.                                                                      |
| **Course_Help**        | I will happily respond to questions here. Especially things regarding the course material, big or small. This involves questions about the course meta, the course material, the tutorials (e.g., "I don't understand this tutorial at all, I am stuck and I think it's the tutorial's fault"), the assignments, etc. If you are using what feels like an unreasonable amount of time on a tutorial then the problem is probably not you. Please don't hold back. |
| **Help_Each_Other**         | The purpose of this channel is to give you a free space to communicate in. You can write to each other for help or even inspiration. I will not be as active, and you can help each other across groups here. You can @ me or take it to A_Q+A if you had a discussion involving multiple people and everyone is stuck. This is for help with setup, debugging, etc. |
| **Random**  | For inspirational links and miscellaneous discussions. Everyone is encouraged to post random DevOps related things here here.                                                                                                         |


---

## Choices and challenges

Create a group document for choices and challenges.

The document doesn't have to be long but enough for you to look up later and recall the challanges. 

**Motivation**: This will help knowledge share across your team. It is also good advice for your main thesis. Show the work!

### Choices

For every major problem you encountered, you must:

- Write down how you made the choice

- Write down relevant considerations your group had 

- Reflect in retrospect on the pros and cons of your choice


### Challenges

For every major choice you've made, you must:

- Write down the considerations you had regarding other choices

- Reflect on the pros and cons of the choice as you make it

- Later on add a reflection on how the choice turned out and unexpected consequences

---

## PR, Please

I really want you to take ownership of the course material and interact with it critically. 

Make Pull Requests to suggest changes. It can be anything from fixing typos, improving explanations or tutorials etc. 




