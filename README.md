# Software-Design-Reflection-
The client for this project was The Gaming Room, a company that wanted to expand its game, Draw It or Lose It, from an Android-only application into a web-based game that could work across multiple platforms The software needed to support multiple teams and players, allow users to check whether names were already in use, and operate well in a distributed environment. To support that, I designed the system using object-oriented principles and recommended a Linux-based server environment with a browser-based client model so the game could scale more easily and be accessible across different operating systems.    

What I Did Well

One thing I think I did particularly well in this documentation was connecting the client’s business needs to actual design decisions instead of just listing technical ideas. I explained why choices such as using the singleton pattern for GameService, inheritance through a shared Entity class, and a Linux server platform made sense for this specific project. I also think I did a good job evaluating multiple platform options and then tying my final recommendation back to the client’s goals.    

What Was Helpful About the Design Document Process

Working through the design document was helpful because it forced me to think through the software before jumping into code. It made me break the system into pieces like requirements, constraints, architecture, domain objects, and platform decisions. That process helped me understand not just what the software should do, but also why it should be designed a certain way. I think this kind of planning would make coding more organized and would help prevent confusion later in development.

What I Would Revise

If I could revise one part of my work, I would probably strengthen the recommendations section even more. I think the direction was good, but I could improve it by making each recommendation more detailed and more directly tied to performance, storage, scalability, and security in the context of multiplayer gameplay. I would also polish some of the wording so the final document feels even more refined.

How I Interpreted the User’s Needs

When interpreting the user’s needs, I focused on what The Gaming Room was really asking for: cross-platform access, support for multiple players and teams, reliable name management, and the ability to run in a distributed environment. I made sure those needs showed up throughout the design instead of treating them like isolated requirements. That is important because software design should always start with the user and the client’s goals. If the design ignores what the user actually needs, the system may work technically but still fail in practice.

My Approach to Software Design

My overall approach to designing this software was to start with the business requirements, identify the major constraints, and then build outward into architecture and object design. I looked at the problem from both a technical and practical perspective by comparing platforms, thinking about the relationships between core objects, and considering performance and security. In the future, I would use the same strategy again: start with requirements, model the important domain objects, compare platform options, and make recommendations based on scalability, maintainability, and user experience. That approach helps create software that is not only functional, but also realistic and easier to support over time.
