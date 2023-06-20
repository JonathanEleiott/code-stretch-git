# Team Dynamics

- Understand the different roles on a team
- Project Management Workflow

## Roles

- Product Owner (not generally technical)
  - Has deep knowledge of the project and is the voice of the customer/client
  - Can make decision on the product and provide product guidance to the team
- Architect (technical)
  - Designs the plans and specfications for the project
- Team Lead (technical)
  - responsible for the dev (and sometimes QA) team
  - day-to-day supervision and assigning technical tasks
- Scrum Master (is usually technical, but the job is not technical)
  - keeper of the scrum/agile process (organizing)
  - coach the team and keep focus on scrum/agile processes
  - mediate and negotiate with outside pressures
- Senior Developer (technical)
  - guides the group by reviewing code for accuracy and functionality
- Jr./Mid Developer (technical)
  - write/review code
  - troubleshooting
  - attends development meetings (most times run by the architect or senior developer)
- Quality Assurance Engineer (most times not technical)
  - build out tests that will identify issues
  - create reports for the stakeholders

** Multiple roles may be inhabited by a single person depending on project/team

## Project Planning

- Benefits
  - Improves team communication
  - Easy to track goals/outcomes
  - Saves companies money by reducing delays and scope creep

## Project Management Methodologies

- Waterfall - 5 phases (each phase needs to finish before moving onto the next)
  - Requirements (all poosible requirements are gathered and documented)
  - Design (the system design is prepared based on the requirements)
  - Implementation (the design is broken down into small units. These units are developed and tested for functionality)
  - Verification (the units are integrated into a system after being tested. Any faults and failures are detected after integration)
  - Maintenance (after production, some issues arise and patches are released to fix the issues)

  - Benefits
    - clear structure
    - tested before launch
    - clear requirements
    - easy to measure progress

  - Drawbacks
    - difficult to know all possible requirements at the beginning
    - slow start
    - rigid process means it's hard to make changes during development

- Scrum
  - teams of 5-9 (sometimes memebers take on multiple roles)
  - takes a large project and breaks it into small tasks for individual team memebers to complete

  - Concept/Project Vision/Initiation
    - create a PROJECT backlog and fill it with epics (general feature of the product)
      - As a/the [user role], I want to [product capability] so that [user benefit]
      - As a user, I want to quickly see all of Jim Carrey's information so that I can learn more about him
  - Planning/Estimate
    - create a PRODUCT backlog and fill it with user stories for each epic
    - same format, but quicker implementation than an epic
      - As a user, I want to see a list of all of Jim Carrey's movies so that I can check which movies he's in
      - As a user, I want to see Jim Carrey's bio so that I can quickly learn his background
    - Sprint Planning
      - sprints are generally 2-4 weeks long
      - dev team identifies which user stories to on and assign tickets
      - SPRINT backlog
  - Implementation
    - Daily stand-up
      - 15 minute meetings where each person answers
        - What tasks he/she did yesterday
        - What tasks he/she plans to work on today
        - What issues he/she faced (roadblocks)
      - Burndown Chart
        - X-axis - Time remaining until end of project
        - Y-axis - Amount of tasks (points)
        - Ideal work remaining - Illustrates the perfect pace of the team
        - Actual tasks remaining -  Tracks the tema's actual progress in real-time
    - Devs work on their tickets
  - Sprint Review/Retrospect
    - After each sprint
    - Sprint Review - led by the Product Owner - team members/stakeholders to assess the project's progress
    - Sprint Retrospective - led by the Scrum Master - reflect on experiences, share thoughts, and decide how to optimize the process
      - What did we do well?
      - What did we NOT do well?
      - How can we improve?
    - Product Backlog Grooming -  is the Product Backlog suitable for the next sprint?
    - Back to the Planning/Estimate phase or Product Retrospective if the final deliverable is submitted
  - Release
    - Get the final project deliverables readt and turning them over to the relevant stakeholders

  - Benefits
    - Everybody involved
    - Structured and communication focused
    - Coding simultaneously rather than sequentially (don't wait for previous phase)
    - Adaptation/Changes between sprints

  - Drawbacks
    - Scope creep
    - Lots of meetings

- Kanban
  - very similar to Scrum but without sprints
  - no defined roles (2 are generally used for groups that want more structured)
    - Service Delivery Manager
      - responsible for improving the workflow
      - Lead the daily stand-ups
      - ensures punctual delivery
    - Service Request Manager
      - understand and interprets the clients needs and expectations
      - organizes the backlog and facilitates prioritization
  - continuous flow
  
  - Benefits
    - Board visibility is focused on
    - Encourages collaboration
    - Even better than scrum in adaptation
  
  - Drawbacks
    - Does not show timelines for each phase
    - No clear product roadmap

- Project Board
  - Columns
    - Epics
    - User Stories
    - In Progress
    - Code Review
    - Done
