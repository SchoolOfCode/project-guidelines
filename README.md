# Project Plan Guidelines

## Understand the problem: Part 1

- Take time to understand who the user is, and what their problem is
- Don't take the problem at face value - delve into it - if Henry Ford would've just listened to what people were asking for, he would have just bred faster horses. Instead, he analysed the deeper problem of people wanting to get from A to B as quickly as possible. **Understand the why**!
- What is the underlying value this software should provide
- Are there different stakeholders?
- What are the existing solutions?
- What is bad/good about them?
- How will success be measured?
- What are the most important things to the user?
- What are the most important things to the customer?

## Ideation: Part 1

- Discuss your initial thoughts and find the holes in your understanding

## Understand the problem: Part 2

- From the initial discussions in your team, ask any other questions you need to

## Ideation: Part 2

- Use disney ideation to bring to life lots of different solutions, and hone down your favourites

## Planning: Part 1

- Start planning the tech behind that solution
- A large part of this time should be spent on research:
  - What is out there that can help?
  - Find some inspiration for designing and branding your platform
  - Plan what assets you may need for the client, and what you are missing
- Create low-fidelity wireframes/sketches of the user experience, and really thinking through what makes a good, smooth, and easy user experience
- Plan what data is needed in your application, and what models are needed to represent that data
- Plan the api needed in order to allow developers to interact with that data
- Delve deeper into the front-end:
  - What should it look like?
  - What is the theme / feel / colour scheme?
  - What assets will you need?
  - What will the user be able to do?
  - What will you show the user?
  - How will you get the data into your front-end application?

## Manage

- Managing yourselves as a team is vital to success
- Agree up front how you will manage the project including:
  - How you will keep in contact (regular stand-ups however often you see fit to help each other stay on the same page and address any issues)
  - How you will resolve conflicts (if there's a deadlock of ideas, how will you move forward?)
- What are your responsibilities? (e.g. is someone keeping the team on track with time? is someone the deciding vote/project CEO?)
- How will you handle taking regular breaks, or knowing when you are going too deep into a problem and need to chat to get perspective?

## Planning: Part 2

- Break your plan up into stories and issues
- Estimate the complexity
- Prioritise
- Find out which issues are blockers for others (which things need to be completed before something else can be started)
- Sort what is in your current sprint, what is in your stretch goals, and what is the future vision
- Delegate to pairs

## Track

- Record anything that could be good when reviewing your project
- Remember that you will be telling the story of your project later, so record anything that would help (photos, videos, diagrams, etc)
- Enable yourselves to tell the whole story - ideas that didn't make it, problems that you encountered, how you resolved them or found solutions
- Do you want to measure how effective your estimation was? Agree upfront, and then measure how long it takes compared to what you thought before starting the task

## Tech: Initialise

- This phase is best done as a whole team, everyone gather round one computer and mob program so you are on the same page
- Create a new project folder outside of any existing git repos
- Create two sub-folders: `client` and `server`
- In each of these folders, initialise your codebase (e.g. use express generator for the server, and create-react-app for the client)
- Adapt these generated code bases so they suit your purpose, e.g.
  - turn the express app into a json api
  - change the folder structure of the react app
- Decide on any libraries and frameworks you want to use upfront - do research and agree as a team
- Use GitHub / GitHub classrooms to set up the repos on GitHub
  - This can be a monorepo or microservice style where each service has it's own repo
- Push your initial work up to the repos

## Tech: Build

- All team members should now pull down the repos into the same structure
- Start working on your features
- Remember our process
  - Do not push to master!
  - Branch off from master, naming your branch whatever the issue you are working on is
  - Make small commits as often as possible to ensure nothing can go too wrong!
  - When your issue is complete, raise a pull request
  - Have another member (at least 1) of the team pull it in - take time to review the code together and make sure someone else knows what's happening
  - Once the merge is accepted, delete the branch
  - Start from the top

## Presentation: Plan

- Plan your presentation, and bring the audience along the journey
- All of your team should contribute to the presentation
- Don't fill your slides with text! Tell the story yourselves, and use imagery and data to help paint the picture and emphasise points
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

Agree as a team which tools you will be using for the job. Here are some possibilities

Project Hosting

- Netlify
- Heroku
- AWS

Database Hosting

- MongoDB Atlas

Designing

- Google Sheets
- Balsamiq
- Whiteboards

Project Management

- Storypoint Poker
- GitHub + ZenHub

Project Tooling

- Express Generator
- Create React App
- Prettier
- ES Lint

Communication

- Slack
- Email
- WhatsApp
