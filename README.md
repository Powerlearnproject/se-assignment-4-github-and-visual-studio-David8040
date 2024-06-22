[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15313793&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:
What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.

- GitHub is a developer platform that allows developers to create, store, manage and share their code

- GitHub uses Git software, providing the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration and wikis in each project


Repositories on GitHub:
What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.

- A repository is the most basic element of GitHub. It's a place where one can store his code, his files, and each file's revision history.
- Repositories can have multiple collaborators and can be either public or private.
- In the command line, navigate to the directory where you want to create a local clone of your new 
project
- To create a repository for your project, use the gh repo create subcommand.
- When prompted, select Create a new repository on GitHub from scratch and enter the name of your new project
- The elements includes;
    . Repository visibility
    . Teams & people
    . Manage the forking policy
    . Manage pull request reviews
    . Manage the commit signoff policy
    . Manage the push policy
    . Managing Git LFS objects in archives
    . Email notifications for pushes


Version control with git:
Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?

- Version control, also known as source control, is the practice of tracking and managing changes to software code. 
- Version control systems are software tools that help software teams manage changes to source code 
over time.

-A version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together.
- As developers make changes to the project, any earlier version of the project can be recovered at any time.
- Developers can review project history to find out:which changes were made?


Branching and Merging in GitHub:
What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.

- Branching in GitHub involves creating a divergent line of development separate from the main codebase(often called the master branch or main branch)
- Merging in GitHub combines changes from one branch( source branch) into another( target branch),
tyically the master or main branch.


Pull Requests and Code Reviews:
What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
GitHub Actions:

- A pull request  is a collaborative feature in version control systems like GitHub that enables developers to propose, review, discuss, and integrate changes systematically and transparently into a codebase.
- It promotes code quality, knowledge sharing, and team collaboration in software development projects
- To create and review  a pull rquest follow this;
   . Once you've commited changes to your local copy of the repository, click the Create pull Request icon
   . Check that the local branch and repository you're merging from, and the remote branch and repository you're merging into, are correct. Then give the pull request title and a description
   . Click create


Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.

- GitHub AcTIONS is a continuous integration and continuous delivery(CI/CD) platform that allows me to automate and build, test, and deploy pipeline. 
- One can create workflows that build and test every pull request to his repository, or deploy merged pull requests to production
- Here are five main steps to build a CI/CD pipeline with GitHub actions;
    . Create or Select a Repository
    . Open GitHub Actions in your repository
    . Make Changes to your Code to Trigger your CI/CD pipeline
    . Look at the Workflow Visualizer
    . View the Workflow
    . Check live logs


Introduction to Visual Studio:
What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?

- Visual studio is a powerful developer tool that one can use to complete the entire development cycle in one place.
- It's a comprehensive integrated development environment that one can use to write, edit, debug, and build code. Then deploy his app
- Visual studio features includes;
   . 64-bit IDE
   . .NET 6 support
   . Intellicode
   . Hot reload
   . Find in Files is faster
-The main difference between Visual Studio vs Visual Studio Code is that the first one is a comprehensive Integrated Development Environment(IDE) tool for software development, while the second one is an Extension-based Code Editor


Integrating GitHub with Visual Studio:
Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?

- You can provide the repository UrL directly or search GitHub for the repository you want by typing in the text box. Once you have selected a repository or Pull Request, the VS Code window will reload and you will see the repository contents inthe File Explorer
- The GitHub Repositories extension lets one to quickly browse, search, edit, and commit to any remote GitHub repository directly from within Visual Studio Code, without needing to clone the repository 
locally.


Debugging in Visual Studio:
Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?

- Here are some key debugging tools available in visual studio;
   . Breakpoints-there is regular breakpoints, condional breakpoints( break only when a specified condition is met), and tracepoints( log messages without interrupting execution). Breakpoints allows one to pause execution at specific lines of code, examine variables and call stack, and step through code line by line for detailed inspection.
   . Watch Windows-Local windows displays variables within the current scope. Auto windows automatically displays variables used recently in the current execution context.Watch windows allows you to manually add variables or expressions to monitor their values as you debug.
   . Call Stack Window-this shows the sequence of method calls that led to the current point of execution. It enables navigation through the call hierarchy to understand how control flows through the application
   . Immediate Windows- allows one to execute code or evaluateexpressions interactively during debugging. Useful for testing snippets of code, modifying variables, or calling functions to observe their effects in real-time.
   . Debugging Tools for Windows (WinDbg)-this is integrated within VS and provides advanced debugging capabilities for low-level debugging, analyzing crash dumps, and investigating performance issues. Supports kernel-mode and user-mode debugging scenarios
   . Diagnostic Tools-CPU Usage Profiler; Analyzes CPU usage to identify performance bottlenecks. Memory Usage Profiler; Monitors memory consumption and detects memory leaks or inefficient memory usage. .NET Object ALLOCATION tOOL; Tracks .NET object allocations and helps optimize memory usage in managed code.
   . Exception Settings- Allows one to configure how Visual Studio handles exceptions, including breaking on specific exceptions orignoring certain types of exceptions during debugging
   . Debugging Managed Code- Visual Studio provides robust support for debugging managed languages like c#, VB.NET, and F#. Features include Just-In-Time(JIT) debugging, inspecting managed objects, and debugging multi-threaded applications.
   . Debugging Native Code-Supports debugging native applications written in c++, including examining memory, registers, and disassembly. Integration with WinDbg enhances debugging capabilities for low-level issues.
   . IntelliTrace- Historical Debugging; Allows one to debug applications retroactively by recording events and program state during execution. Helps track down issues that are hard to reproduce by replaying events leading to an error.
   . Code Map Debugger Integration- Visualizes relaionships and dependencies between code elements during debugging. Helps understand how different parts of the application interact and identify potential areas causing issues.

     - Debugging tools in Visual studio collectively provide a comprehensive environment for diagnosing and fixing bugs, optimizing performance, and ensuring the reliability of software applications across various development scenarios
  
     - By using debugging tools effectively,  developers can systematically identify, diagnose, and resolve issues in their code, ensuring software quality and reliability. Debugging is not only about fixing bugs but also about understanding the behaviour of your code and improving its design and performance.

Collaborative Development using GitHub and Visual Studio:
Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.

- GitHub and Visual Studio Code together create a powerful environment for collaborative development. 
- They streamline version control, enable efficient code review workflows with pull requests, support real-time collaboration through extensions like Live Share, automate CI/CD pipelines with GitHub 
actions, and provide robust project management tools. This integration enhances productivity, promotes code quality, and facilitates seamless teamwork across distributed teams working on projects hosted on GitHub.

- A real- world example of a project that benefits from integration of GitHub and Visual Studio is
  Web application.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
