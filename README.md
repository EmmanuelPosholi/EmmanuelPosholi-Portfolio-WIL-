# EmmanuelPosholi-Portfolio-WIL-

# Student: Emmanuel Posholi 
# Student Number: 222144408
# Assessement: Project Presentation 3 Github Portfolio

# YES Platform – Youth Employment Service

## Work Integrated Learning Portfolio

---

# Project Overview

As part of my Work Integrated Learning placement, I helped to develop the **YES Platform (Youth Employment Service)**, a mobile employment and work experience platform that seeks to link South African youth to employment and host enterprises.

The website offers different experiences for youth candidates and host enterprises. Youth can build profiles, add skills and career interests, look for opportunities, view company profiles, submit weekly activity logs and create a record of verified skills and work experience.

The host companies can register company profiles, design work opportunities, view recommended candidates, check the skill profile of applicants, assign, and give feedback.

The platform also employs a multi-signal matching system that takes into account a range of factors including skills, geographical location, and career aspirations, to suggest appropriate matches and opportunities.

## My Role

I contributed to the project from both a **Full-Stack Development** and **Quality Assurance (QA)** perspective.

My responsibilities included:

- Frontend development and testing
- Backend API integration
- Testing application functionality
- Identifying and reporting bugs
- Validating user workflows
- Testing frontend and backend integration
- Reviewing functionality from the user's perspective
- Contributing to improvements and fixes

## Technologies Used

- React Native
- Expo
- TypeScript
- Python
- Flask
- SQLite
- NumPy
- REST APIs
- Git
- GitHub

---

# 1. Agile Team Charter

## Evidence

Our team used an Agile Development methodology while building the YES Platform, organizing development efforts, reporting on development progress and working towards common goals of the project.

Together, we wanted to create a platform which strengthens the link between youth and meaningful work experiences and provide host businesses with the capabilities to manage opportunities, candidates and workplace development.

### Team Objectives

- Build a functional application for youth and host enterprises.
- Provide separate experiences for youth and host users.
- Allow youth to create and maintain skills profiles.
- Allow host enterprises to create and manage opportunities.
- Develop a matching system based on multiple factors.
- Allow hosts to review and assign candidates.
- Track candidate work experience and development.
- Test functionality throughout development.
- Identify and resolve defects.

### Working Agreements

- Communicate development progress regularly.
- Break larger features into smaller manageable tasks.
- Use Git and GitHub for source code management.
- Test functionality before considering work complete.
- Communicate blockers and technical issues.
- Review completed functionality against requirements.
- Test complete workflows after integration.

## Team Charter Evidence

The following evidence shows the planning and working agreements used by the team during the project.

### Team Charter / Planning Screenshot

> <img width="559" height="527" alt="project charter" src="https://github.com/user-attachments/assets/089b6bc4-2497-4c34-9746-fb9f847eaf4e" />


<img width="559" height="527" alt="project charter2" src="https://github.com/user-attachments/assets/e57d8c22-19a7-409f-bec4-58d021f83f37" />

<img width="537" height="517" alt="project charter3" src="https://github.com/user-attachments/assets/2788dfb8-d393-47ce-b57d-1e3839ef976d" />


## Reflection

Working within an Agile team helped me understand that software development involves much more than writing code.

A big lesson I learned was that communication between development and testing is essential. Since I worked both as a Full-Stack Developer and an Engineer in QA, I had to make sure that a feature was technically functional and that it was user-friendly.

In addition, I have also understood how to communicate problems at an early stage. A small development flaw in the front end, back end API, or database could have a significant impact on a user's workflow.

On the whole it was good to work in the team as it helped me to expand my knowledge of communication, accountability, collaboration and software development in an Agile environment.

---

# 2. User Stories and Tasks

## Evidence

User stories were used to describe features from the perspective of the users of the YES Platform.

The two main users were:

1. Youth candidates
2. Host enterprises / SMEs

Examples of user stories include:

| ID | User Story | Priority |
|---|---|---|
| US01 | As a youth user, I want to register my skills and career interests so that I can receive relevant work opportunities. | High |
| US02 | As a youth user, I want to view recommended opportunities so that I can find work suited to my profile. | High |
| US03 | As a youth user, I want to submit weekly activity logs so that my work experience can be recorded. | High |
| US04 | As a host enterprise, I want to register my company so that I can participate as a host on the platform. | High |
| US05 | As a host enterprise, I want to create work opportunities so that suitable youth can be identified. | High |
| US06 | As a host enterprise, I want to review candidate profiles so that I can make an informed placement decision. | High |
| US07 | As a host enterprise, I want the system to recommend suitable candidates so that I can identify candidates efficiently. | High |
| US08 | As a host enterprise, I want to assign a candidate manually so that I remain responsible for the final placement decision. | High |
| US09 | As a host enterprise, I want to provide feedback so that candidate performance can be recorded. | Medium |
| US10 | As a user with unreliable connectivity, I want my actions to synchronise when connectivity returns so that my work is not lost. | Medium |


## Example User Story Breakdown

### Candidate Matching

**User Story:**

> As a host enterprise, I want the system to recommend suitable candidates so that I can identify candidates efficiently.

**Development Tasks:**

- Retrieve registered youth profiles.
- Retrieve task requirements.
- Compare candidate skills with required skills.
- Consider geographical proximity.
- Consider career goal alignment.
- Calculate candidate matching scores.
- Rank candidates.
- Generate matching reasons.
- Return results through the API.
- Display ranked candidates.
- Test candidate ranking.

## Reflection

Working with user stories helped me understand how requirements can be translated into development work.

Instead of immediately thinking about technical implementation, user stories encouraged me to first consider what the user wanted to achieve.

Candidate matching, for example, appears to the user as one feature. Breaking it into tasks showed that it depended on several components, including profile information, task requirements, API communication, matching calculations and the user interface.

From a QA perspective, user stories also provided clear expected behaviour that could be compared against the completed functionality.

---

# 3. Product Backlog

## Evidence

The Product Backlog contained the functionality, improvements and technical work required for the YES Platform.

Items were prioritised based on their importance to the main application workflows.

| ID | Backlog Item | Type | Priority | Status |
|---|---|---|---|---|
| PB01 | Youth onboarding | Feature | High | Done |
| PB02 | Host onboarding | Feature | High | Done |
| PB03 | Youth profile management | Feature | High | Done |
| PB04 | Host company profiles | Feature | Medium | Done |
| PB05 | Multi-signal candidate matching | Feature | High | Done |
| PB06 | Host task creation | Feature | High | Done |
| PB07 | Task lifecycle management | Feature | High | Done |
| PB08 | Candidate profile inspection | Feature | High | Done |
| PB09 | Candidate assignment | Feature | High | Done |
| PB10 | Weekly activity logs | Feature | Medium | Done |
| PB11 | Micro-credential verification | Feature | Medium | Done |
| PB12 | Host feedback and ratings | Feature | Medium | Done |
| PB13 | Offline action synchronisation | Feature | Medium | Done |
| PB14 | Partner routing | Feature | Medium | Done |
| PB15 | API connection configuration | Technical | Medium | Done |

## Reflection

The Product Backlog helped me understand the importance of prioritisation during software development.

Not every feature has the same level of importance. Core functionality such as youth onboarding, host onboarding, task creation, candidate matching and candidate assignment needed higher priority because other functionality depended on them.

I learned that a Product Backlog is not simply a list of features. It provides a structured view of the work required and helps the team determine which functionality should be addressed first.

---

# 4. Sprint Backlog

## Evidence

While the Product Backlog represented the overall work required for the application, the Sprint Backlog contained the work selected for a particular sprint.

For example, a sprint focusing on candidate matching and assignment could contain the following:

| Task | Related Story | Status |
|---|---|---|
| Retrieve youth candidates | Candidate Matching | Done |
| Implement skill matching | Candidate Matching | Done |
| Implement location consideration | Candidate Matching | Done |
| Calculate candidate score | Candidate Matching | Done |
| Rank candidates | Candidate Matching | Done |
| Display matching reasons | Candidate Matching | Done |
| Create candidate inspection screen | Candidate Review | Done |
| Implement assignment endpoint | Candidate Assignment | Done |
| Save candidate assignments | Candidate Assignment | Done |
| Test candidate matching | QA | Done |
| Test assignment workflow | QA | Done |

## Reflection

Working with smaller groups of tasks helped me understand why Agile development uses sprints.

Trying to develop the entire application at once would make it difficult to track progress and identify problems. Dividing work into smaller goals made the development process more manageable.

I also learned that features depend on previous work. For example, candidate matching depends on youth profiles and host opportunities being available. Candidate assignment then depends on the matching and candidate profile functionality.

The sprint approach was also useful from a QA perspective because functionality could be tested as it was completed rather than waiting until the entire application was finished.

---

# 5. Agile Logbook

## Evidence

The Agile Logbook records development activities, progress, challenges, testing activities and lessons learned throughout the project.

## Agile Logbook Evidence

### Google Sheets Logbook

<img width="1006" height="768" alt="google sheets" src="https://github.com/user-attachments/assets/077d2a18-1b6f-40af-896b-7eda6f5fbeca" />


<img width="1357" height="521" alt="google sheets1" src="https://github.com/user-attachments/assets/9ed7d402-cc51-416f-ae75-a41e5273ae56" />



### Stand-Up Evidence

<img width="1063" height="551" alt="standup report" src="https://github.com/user-attachments/assets/9fd24ed1-db23-47c0-8ba5-a7ad1f558e08" />

<img width="1119" height="485" alt="standup report 1png" src="https://github.com/user-attachments/assets/35836f26-7b50-43f3-9775-e9a25789d1cc" />


## Example Logbook Entry

### Development Activity – Candidate Matching

**Work Completed:**

Worked with the candidate matching functionality. The system considered multiple factors when ranking candidates, including skills, location and career goals.

**Challenge:**

Candidate suitability could not be determined accurately using only one factor.

**Action Taken:**

Multiple signals were considered when calculating candidate rankings, and reasons were provided to explain recommendations.

**What I Learned:**

I learned that recommendation systems can provide more useful results when multiple pieces of information are considered. I also learned that users should be able to understand why the system has made a recommendation.

---

## Example Logbook Entry – Quality Assurance

**Work Completed:**

Tested different parts of the application and reviewed complete user workflows.

Testing included:

- User registration
- Profile updates
- API communication
- Task creation
- Candidate matching
- Candidate assignment
- Weekly logs
- Host feedback
- Navigation
- Data persistence

**Challenge:**

Some problems only became visible when multiple parts of the system were connected.

**Action Taken:**

Complete workflows were tested in addition to individual features.

**What I Learned:**

I learned that testing individual components is important, but it is not enough. Integration testing is necessary because some defects only become visible when the frontend, backend and database interact.

---

## Agile Logbook Reflection

Maintaining a record of development activities helped me reflect on how the application changed throughout development.

The project showed me that software development is an iterative process. Features are planned, developed, tested and improved based on the results of testing and feedback.

Working from both a Full-Stack Development and QA perspective gave me a better understanding of this process.

I started thinking more about questions such as:

- What happens if the user enters incorrect information?
- What happens if the API is unavailable?
- What happens if no candidates match?
- What happens if data is missing?
- Can a user move a task into an invalid state?
- Is information being saved correctly?
- Does the complete workflow work?

This changed the way I approached development and testing.

---

# 6. Application Evidence

This section demonstrates the actual YES Platform that was developed.

## Role Selection

<img width="866" height="768" alt="image" src="https://github.com/user-attachments/assets/69b02ce7-795b-41bb-9016-32db28b8adc3" />


## Youth Onboarding

## Youth Dashboard

<img width="866" height="768" alt="image" src="https://github.com/user-attachments/assets/14ad136f-d586-4053-8a61-60a53b0bdb7f" />


## Task Creation


<img width="866" height="768" alt="image" src="https://github.com/user-attachments/assets/9bcc8197-63d3-4b01-8b22-4e71604974c9" />


# 7. GitHub Development Evidence

Git and GitHub were used during development to manage source code and track changes to the application.

## GitHub Repository

<img width="866" height="768" alt="image" src="https://github.com/user-attachments/assets/2e12dbd3-10a5-42cf-9934-011b1d3890be" />

## Commit History

<img width="866" height="768" alt="image" src="https://github.com/user-attachments/assets/c20a93dd-19d1-45ad-b1ed-4120057b8b5b" />


# 8. Skills Developed

Working on the YES Platform allowed me to develop both technical and professional skills.

## Technical Skills

- React Native
- TypeScript
- Python
- Flask
- SQLite
- REST APIs
- Git and GitHub
- Mobile application development
- Frontend/backend integration
- Database integration
- Software testing
- Debugging
- API testing

## Professional Skills

- Communication
- Teamwork
- Problem-solving
- Critical thinking
- Time management
- Task prioritisation
- Quality Assurance
- Requirements analysis

---

# 9. Overall Reflection

The YES Platform project was an important part of my Work Integrated Learning experience because it allowed me to apply concepts that I had previously learned in an academic environment to a practical software development project.

One of the biggest differences I experienced was that real software development requires continuous problem-solving.

Implementing a feature is only one part of the process. The feature must also integrate with the rest of the application, handle unexpected situations and provide the intended experience to the user.

My experience working across Full-Stack Development and Quality Assurance was particularly valuable.

Development taught me how different parts of an application communicate with each other, while QA taught me to question assumptions and look for situations where the application may not behave as expected.

I also gained a better understanding of Agile development.

User stories helped connect technical development to user needs. Product and Sprint Backlogs helped organise and prioritise work. Breaking features into smaller tasks made development more manageable, while testing and reflection helped identify areas that could be improved.

Overall, the YES Platform helped me grow as both a developer and tester and gave me a better understanding of how software is planned, developed, tested and improved within a professional environment.

---

# 10. Conclusion

The YES Platform demonstrates the knowledge and practical skills I developed during my Work Integrated Learning experience.

The project brought together several areas of software development, including mobile development, backend development, databases, APIs, matching logic, testing and Agile project management.

Through this experience, I improved my technical abilities while also developing professional skills such as communication, teamwork, critical thinking and problem-solving.

The experience has given me a stronger foundation for continuing my career in software development and Quality Assurance.
