# prism-t1
The repo/project I chose: [Hermes Agent](https://github.com/NousResearch/hermes-agent)

# 1. OVERVIEW

## What does the software do?
It's an agent that runs on your own PC continuously learns from every chat. It keeps a record of all the chats so far and always answers with past experience (which already other AI's do now though). But, this is an AI teammate because it not just writes code but can also execute it on your personal computer's terminal or IDE. It can also browse the web. You can also automate tasks and control comms apps. Similar to openClaw, but it can spawn multiple sub agents to work in parallel with it. 

## What problem does it solve?
- One thing is it keeps a log of all the previous chats and answers based on it. More persistent than current models (supposedly).
- It can do stuff in real time (Biggest advantage!). Can access terminal, file systems and browse autonomously (includes automating tasks).
- It keeps learning and gets better over time.

## Who would typically use it?
- Developers who want to automate repetitive tasks (live debugging, mangaing servers, other coding tasks)
- Startups which aim to build AI-powered products faster, and run them assistants 24/7.

# 2. REPOSITORY STRUCTURE
## src/
- This contains the actual working code of the project (agent in this project).
- Has the code which handles the logic for the hermes AI (including memory, tools, etc) [Brain of the project]

## docs/
- Has guides and explanation of the project.
- Content written on how to install and use the agent, like a manual.

## tests/
- Testing arena for the project where the developer tests different features of the agent and catches the bugs before releasing it.

## examples/
- Shows how to use the agent in real situations by giving an example use case.
- Great way to demonstate its features.

## scripts/
- Has all the setup and scripts required to instal and run the project. (Libraries,tools etc## ##.)

## Readme.md
- Overview of the project
- Explains what the agent does and how to get started.

# 3. Technologies used

## Programming languages
- Mainly written in Python (cause Py is mostly use for building AI due to its easy to use functions developed for ML, probability and statistics)

## Frameworks / Libraries
- LLM integrations like local or API based modules of other pre built AIs.
- Includes librareis like asyncio, pydantic, etc.

## Build Tools
Uses pip for packaging. CLI commands to run the agent.

## Database
- Uses file based storage for memory.
- Stores past experiences locally. So, it might increase its storage size on prolong usage.
- Uses lightweight databse (JSON files).
  
# 4. Contribution Workflow

## Does it have a CONTRIBUTING.md file?
- Haven't found a dedicated contribute.md file in the repo.
- Closed to their own team (Claude is their team member).
- PRs are still followed though.
- No strict guidelines on open source contribution

## How are issues used?
- To report bugs
- Request new features
- Ask questions - Helps track problems and improving the project.

## How do contributors submit pull requests?
 - Fork the repo
 - Make changes in their own copy
 - Submit a Pull Reqeust (PR)
The PRs will be reviewed by the maintainer and can consider merging to the main project if found useful.
- Useful to fix bugs, add new featuresm and improve documentation.

# 5. Something that interested me
- Found it interesting cause this project is also being managed and developed by Claude officially. (To rival against OpenClaw) This looked like an interesting competition after claude sued OpenClaw for their previous name (ClaudeBot). 

