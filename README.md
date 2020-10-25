# CS230 Software Design Document by Jon Frodin

-Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The client in this design document was a company called The Gaming Room. They had a drawing application for Android smartphones. They were looking to convert this to a web-based game to be used across many platforms. This was to be a browser game and it was going to use a repository of images and render them slowly (30 seconds) allowing people to guess what it was as the image became more clear.

-What did you do particularly well in developing this documentation?
I believe I did the evaluation particularly well in this document. I thoroughly went through each of the operating systems and how they act when used as servers. I also went into great detail on the programming environments on each of those operating systems and whether the popular choices were cross-compatible with other operating systems. I think I gave a rather extensive breakdown of what each operating system would lead the user or developer to expect when looking at the server or client side. Since the clients were all web browsers, I went more into statistics on how they are used and some differences between them overall since they work in such a similar fashion and they are all free.

-What about the process of working through a design document did you find helpful when developing the code?
I didn't actually find the document helpful in developing code. Well, I suppose I did in one very limited instance. Without this document, I would not have really known that this was going to be a web-browser based application. That was not made clear in any of the documents of this course. Everything said that they had an Android game they were looking to bring to other platforms. That's all well and good, but it does not imply that they wanted to convert it to a browser based game. Because of editing this document, that became more clear in Module 4 of this class when we did the bulk of the actual coding. I wasn't sure what we were even doing with dropwizard, and then a chat with the professor and some references to this document helped me get that it wasn't rebuilding the application for the different operating systems, it was building it for a web server accessible via web browsers. That made all the difference in the code, but only insofar as I finally understood what we were doing, not the actual how we were doing it. That part I had already finished because it was implementing rather vaguely explained concepts on half-done code.

-If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I would revise the executive summary and the design constraints. Initially I had written those two sections assuming we were trying to use an Android app as the basis for a program to install on several operating systems. I also wrote it based on what the software actually needed to do (allow multiple users, teams, etc.) but that was not correct at all. Knowing what I know now, about what the project actually involved, I would go back and add more about how to convert programs to web applications from standalone applications and do more research in that area. I would also adapt my design constraints with that solid end goal in mind.

-How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
Many of the user's needs were incorporated into the design constraints section. There, I discussed security, storage, memory, and functional requirements like teams and multiplayer. It is important to consider the needs of the user throughout the design document because they are the ones paying the bills. Apart from simple finances, though, it is important because they are the ones who came to you with a vision for their product. If you do not keep their vision in mind throughout the design and development, then you'll end up with a deliverable that doesn't match what they wanted from you. You don't want to find out, late in the game, that you did something based on an assumption you made about what the user wanted without referencing their stated needs and find out that you have to re-do a massive amount of work to implement some change that they wanted from the beginning.

-How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I was actually rather confused throughout this whole process. The approach I had was to read the requirements and to read the requirements for submission and make sure I did my best to include everything mentioned in both. The software itself, we didn't really design at all. We just finished some methods and finished some java gaps and that was it. In the future, I would reach out for help week 1 if I was not clear about something and clear it up immediately. Then, with that hazard out of the way, I would try to keep pace every week doing exactly what I did, just more targeted. I would research, take notes, and apply it to my documentation.
