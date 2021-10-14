# Final Project Guidelines

## Team

- The most important part of any project is making sure the team are all bought into it.
- In great teams, each member puts the team above themselves. Egos are left at the door; we're all in it to help each other.
- What are the strengths, preferences, weaknesses, and how can you all work together to maximise each others' potential?
- How will you keep it a happy, fun, and effective team environment?
- Remember all your teamwork and self-awareness sessions.

## Manage

- Managing yourselves as a team is vital to success.
- Agree up front how you will manage the project including:
  - How you will keep in contact (regular stand-ups however often you see fit to help each other stay on the same page and address any issues)
  - How you will resolve conflicts (if there's a deadlock of ideas, how will you move forward?)
  - Who will facilitate each meeting - will it be random or a rota? Or one person for each type of meeting?
- What are your responsibilities? (e.g. is someone keeping the team on track with time? is someone the deciding vote/project CEO?)
- How will you handle taking regular breaks or knowing when you are going too deep into a problem and need to chat to get perspective?
- Decide on a strategy for dividing up work and still keeping people in the loop and working as part of a team.

## Understand the problem: Part 1

- Take time to understand who the user is and what their problem is.
- Don't take the problem at face value - delve into it. If Henry Ford would've only listened to what people were asking for, he would have just bred faster horses. Instead, he analysed the deeper problem of people wanting to get from A to B as quickly as possible. **Understand the why**!
- What is the underlying value this software should provide?
- Are there different stakeholders?
- What are the existing solutions?
- What is bad/good about them?
- How will success be measured?
- What are the most important things to the user?
- What are the most important things to the customer?

## Ideation: Part 1

- Discuss your initial thoughts and find the holes in your understanding.

## Understand the problem: Part 2

- From the initial discussions in your team, ask any other questions you need to.

## Ideation: Part 2

- Use Disney ideation to bring to life lots of different solutions, and hone down your favorites.

## Planning: Part 1

- Create [user personas](https://www.hubspot.com/make-my-persona) to get to know your users
- Create [user stories](https://www.atlassian.com/agile/project-management/user-stories) to help map through what a user wants to do and why
- Start planning the tech behind that solution.
- A large part of this time should be spent on research:
  - What is out there that can help?
  - Who can you speak to/get information from for user research?
  - Find some inspiration for designing and branding your platform.
  - Plan what assets you may need for the client and what you are missing.
- Create low-fidelity [wireframes/sketches](https://www-freecodecamp-org.cdn.ampproject.org/c/s/www.freecodecamp.org/news/what-is-a-wireframe-ux-design-tutorial-website/amp/) of the user experience, and really think through what makes a good, smooth, and easy user experience.
- Plan what data is needed in your application and what models are needed to represent that data.
- Plan the API needed in order to allow you and other developers to interact with that data.
  - Specify what routes you will have and what the response will be.
- Delve deeper into the front-end:
  - What should it look like?
  - What is the theme / feel / color scheme
    - [Coolors](https://coolors.co/)
    - [Color Palette Generator](https://colors.muz.li/)
    - [Color Mind](http://colormind.io/)
    - [Adobe Color](https://color.adobe.com/create/color-wheel)
  - What assets will you need?
  - What will the user be able to do?
  - What will you show the user?
  - How will you get the data into your front-end application?

## Planning: Part 2

- Break your plan up into epics, milestones and issues.
- Keep track using Jira.
- Estimate the complexity using story point poker.
- Prioritise.
- Find out which issues are blockers for others (which things need to be completed before something else can be started).
- Plan your sprints.
  - We recommend no longer that a week.
  - Sort what is in your current sprints, what is in your stretch goals, and what is the future vision.
- Delegate to pairs/threes.

## Track

- Record anything that could be good when reviewing your project. Take pictures and record from the start and all the way through!
- Remember that you will be telling the story of your project later, so record anything that would help (photos, videos, diagrams, etc.).
- Enable yourselves to tell the whole story - ideas that didn't make it, problems that you encountered, how you resolved them or found solutions, etc.
- Do you want to measure how effective your estimation was? Agree upfront, and then measure how long it takes compared to what you thought before starting the task.

## Tech: Initialise

- This phase is best done as a whole team with everyone gathering round one computer and mob programming so you are on the same page.
- Create a new project folder outside of any existing git repos
- Create two sub-folders: `client` and `server`
- In each of these folders, initialise your codebase (e.g. use dotnet new webapi for the server, and create-react-app for the client)
- Adapt these generated code bases so they suit your purpose, e.g. changing the folder structure of the React app.
- Decide on any libraries and frameworks you want to use upfront - do research and agree as a team.
- We will provide you with empty GitHub classrooms.
  - This can be a monorepo or microservice style where each service has its own repo.
- Push your initial work up to the repo(s).
- Align your Prettier config to avoid messy merges.

## Tech: Build

- All team members should now pull down the repos into the same structure
- Start working on your features
- Remember the process:
  - **Do not push to master!**
  - Branch off master, creating a dev branch.
  - Branch off from dev, naming your branch whatever the issue you are working on is.
  - Make small commits as often as possible to ensure nothing can go too wrong!
  - **Co-author your commits** - it'll be important to show you've contributed even when pairing/mobbing; [click here to see how](https://help.github.com/en/github/committing-changes-to-your-project/creating-a-commit-with-multiple-authors).
  - **You may find it useful to raise a pull request early on in the process**; we'd suggest when you think you are 30% done (ask the team - "here's what I'm thinking - any suggestions early on?", and when you think you are 90% done: "I think I've cracked it. Any last pointers before it's ready to submit?").
  - When your issue is complete, raise a pull request against dev.
  - Have another member (at least one) of the team pull it in - take time to review the code together and make sure someone else knows what's happening.
  - **Request a review from a School of Code Coach**; these reviews will help keep you on the right track, prompt you to take in best practices, and keeps us informed on your progress so we can spot problems before they become runaway trains!
  - Once the merge is accepted, delete the branch.
  - You can then raise a pull request from dev into master.

## Presentation: Plan

- Plan your presentation, and bring the audience along the journey.
- All of your team should contribute to the presentation.
- Don't fill your slides with text! Tell the story yourselves, and use imagery and data to help paint the picture and emphasise points.
- A guideline structure for a project presentation could be:
  - Introduce the team
  - Problem: Introduce the problem how you saw it
  - Market: Who is this for, and is there a wider need for the solution?
  - Solution: LIVE Demo time. Show off your solution
  - Journey: How did you get to your solution - from ideation to delivery
  - Management: How did you manage your project
  - Analysis: Give a summary of how the project went, or what value it delivers
  - Vision: Where could this project go - and have you made any steps to help see not only the far-off vision, but where you could take it immediately given more time?
  - Q & A
- Practice by running through the presentation a few times with your team if possible, especially the live demo and product walk-through

## Present

- Take your time, and enjoy it!

## Tools

Agree as a team which tools you will be using for the job. Here are some possibilities, but it's by no means limited to this list!

Project Hosting

- Netlify
- AWS
- Heroku
- Docker

Database Hosting

- AWS
- Heroku
- Google Cloud
- Azure
- Firebase
- MongoDB Atlas

Designing

- Figma
- Google Sheets
- Balsamiq
- Whiteboards
- Draw.io (download VS code extension!)

Project Management

- Jira
- GitHub Projects
- Trello

Project Tooling

- Next.JS
- Create React App
- Prettier
- ES Lint
- Storybook
- Gatsby

Testing

- Jest
- Cypress
- React Testing Library

Continuous Integration and DevOps

- GitHub actions
- CircleCI
- Travis
- Terraform

Bug Tracking / Detection / Logging

- Sentry
- Log Rocket

Communication

- Slack
- Email
- WhatsApp
- Zoom
- Discord
