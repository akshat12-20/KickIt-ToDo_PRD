# KickIt : A to-do website for everyone

## Purpose & Objective
- <span style="font-size: larger;"><u>Purpose</u></span>: Tracking tasks is crucial for their completion. However, using a diary/notebook is very unstructured. Carrying and storing multiple diaries is impractical, and even minor edits can make things messy.There is a high chance of forgetting deadlines.

- <span style="font-size: larger;"><u>Objective</u></span> : KickIt is here to provide structured, easily accessible, always available, user-friendly website to track any tasks either a day-to-day one or a highly important one with timely reminders, to ensure that no deadlines are missed.

## Scope 
- <span style="font-size: larger;"><u>In-Scope</u></span>:
    - Login via Google/mobile number
    - To-do categories
    - Date-wise structuring
    - Priority option
    - Timer option
    - Deadline reminders
    - Gmail integration
    - Self customizable themes
    - Strategy support
    - Daily quotes
- <span style="font-size: larger;"><u>Out-of-Scope</u></span>:
    - Android/IOS app development
    - Note-taking 

## Features & Requirements
- <span style="font-size: larger;"><u>Priority-1</u></span> :
    - <u>Multiple categories</u>: Allows users to create multiple to-do sections, for e.g., work, daily chores, etc to make it structured & focused. 
    - <u>Sub-tasks</u>: Allows users to divide each task into sub-tasks, making it easier for users to complete them.
    - <u>Priority & timer option</u>: Allows users to set priority of the tasks either with the numbers or colours. Also provides timer option to track the time taken to complete a particular task.
    - <u>Deadline reminders</u>: Users receive three reminders via whatsapp/email. Three days before the deadline, 24 hours before the deadline & a missed reminder after the deadline.
    - <u>Strategy support</u>: The missed tasks are automatically transferred to strategy section without the date, priority & timer content. There users are allowed to reset the particular task. 
    - <u>Gmail integration</u>: Allows users to integrate their gmail accounts in a specific section and provides them with a feature to save important mails in the saved section.
    - <u>History</u>: The history of the previous data and timer content restores. So that users can track their progress.
    - <u>Themes & daily quotes</u>: There are many themes available but users can customize them upto a extent according to their needs. Also one new deep quote updates daily on the main screen to motivate the users.
- <span style="font-size: larger;"><u>Priority-2</u></span> :
    - Multi-language support for the system.
    - AI integration feature for the evaluation & feedback.

## User Stories
- As a user, I want reminders so that my deadlines can't be missed.
- As a user, I want timer associated with the task so that I can track my progress.
- As a user, I want different categories for my to-do list so that I can be more focused & structured.

## Technical Requirements
1. <u>Frameworks</u>: React, Nextjs, Nodejs.
2. <u>Database</u>: MySQL
3. <u>Infrastructure</u>: cloud-based hosted on AWS.

## Design Requirements
- The design must be responsive.
- Use a clean, un-cluttered & minimalist design with vibrant & calming colors.

## Non-Functional Requirements
- The website should load in less than 2 seconds for all pages.
- The system should handle upto 10,000 concurrent users without performance degradation.

## User Journey Flow
- User visits the website→ Login using google/phone number→ on the main page, a quote is displayed → from the lefi-side bar, choose one of them(to-do, strategy, integration, themes, saved).
- If chooses to-do→ choose category→ write down tasks with date, priority, deadlines→click on a task to enter it→ Divide the task into sub-tasks with same parameters.
- If choose strategy→ enter the date and other parameters for the missed tasks to reset them.
- If choose integration→ login gmail account→ see all the mails data wise→ click the star icon to transfer it to the saved section.

## Constraints
- The MVP must be ready within 5 months from the product start date.
- The product is not designed with features to support accessibility for visually impaired users.

## Asumptions
- Login & to-do list features will be sufficient for MVP.

## Success Metrics
- Achieve 90% user satisfaction within 3 months of launch.
- Increase productivity of 50% users to 80% within a year of launch.

## Timeline
The final product must be ready to launch within 1.5 years.

## Future Enhancements
- AI integration for evaluation & feedback.
- Multi-language support.



