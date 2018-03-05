## Questions about Software Architecture

* When is a cache not useful or even dangerous? [[A]](http://www.slideshare.net/betclicTech/minitraining-to-cache-or-not-to-cache)
* Why does [Event-Driven Architecture](https://en.wikipedia.org/wiki/Event-driven_architecture) improve scalability? [[A]](https://en.wikipedia.org/wiki/Event-driven_architecture#Extreme_loose_coupling_and_well_distributed)
* What makes code readable? [[A]](https://code.tutsplus.com/tutorials/top-15-best-practices-for-writing-super-readable-code--net-8118)
* What is the difference between emergent design and evolutionary architecture? [[A]](https://www.ibm.com/developerworks/library/j-eaed19/index.html)
* Scale out vs scale up: how are they different? When to apply one, when the other? [[A]](https://www.brianjgraf.com/2013/05/17/scalability-scale-up-scale-out-care/)
* How to deal with failover and user sessions?
* What is CQRS (Command Query Responsibility Segregation)? How is it different from the oldest Command-Query Separation Principle? [[A]](http://programmers.stackexchange.com/questions/165120/separation-versus-segregation)
* The so called "multitier architecture" is an approach to design a client–server system aimed to keep physically and logically separated presentation, application processing, data management and other functions. The most widespread of the multitier architectures is the three-tier architecture. Would you discuss the pros and cons of such approach? [[A]](http://stackoverflow.com/questions/4577587/mvc-vs-3-tier-architecture)
* How would you design a software system for scalability? [[A]](https://elastisys.com/2015/09/10/scalability-design-principles/)
* Someone gave the name "The "C10k problem" to the problem of optimising network sockets to handle over 10.000 open connections at once. While handling 10.000 concurrent clients is not the same as handling 10.000 open connection, the context is similar. It's a tough challenge anyway, and no one is expected to know every single detail to solve it. It may be interesting to discuss the strategies you know to deal with that problem. Would you like to try? [[A]](https://www.youtube.com/watch?v=73XNtI0w7jA)
* How would you design a decentralized (that is, with no central server) P2P system? [[A]](http://abdulapopoola.com/2013/03/12/design-patterns-pub-sub-explained/)
* pubsub vs observer [[A]](http://stackoverflow.com/questions/15594905/difference-between-observer-pub-sub-and-data-binding)
* When would you apply horizontal scaling and when vertical scaling? [[A]](https://www.g2techgroup.com/horizontal-vs-vertical-scaling-which-is-right-for-your-app/) [[A]](http://stackoverflow.com/questions/11707879/difference-between-scaling-horizontally-and-vertically-for-databases)
* You may recall that Common Gateway Interface (CGI) is a standard protocol for web servers to execute programs (CGI scripts) that execute as Command-line programs on a server, and that dynamically generate HTML pages when invoked by a HTTP request. Perl and PHP used to be common languages for such scripts. In CGI, a HTTP request generally causes the invocation of a new process on the server, but FastCGI, SCGI and other approaches improved the mechanism, raising the performance, with techniques such as preforking processes. Can you imagine why has't CGI eventually win, and was instead replaced with other architectural approaches?
* How would you defend the design of your systems against Vendor Lock-in?
* What are the disadvantages of the [Publish-Subscribe pattern](https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern) at scale?
* What's new in CPUs since the 80s, and how does it affect programming? [[A]](http://danluu.com/new-cpu-features/)
* In which part of the lifecycle of a software performance should be taken in consideration, and how? [[A]](https://airbrake.io/blog/sdlc/what-is-the-software-development-life-cycle)
* How could a Denial of Service arise not maliciously but for a design or architectural problem?
* What’s the relationship between Performance and Scalability? [[A]](http://apmblog.dynatrace.com/2008/09/11/performance-vs-scalability/)
* When is it OK (if ever) to use tight coupling? [[A]](http://stackoverflow.com/questions/19976273/where-loose-and-tight-coupling-would-be-used-as-a-real-scenario)
* What characteristic should a system have to be Cloud Ready? [[A]](http://www.ibm.com/developerworks/websphere/techjournal/1404_brown/1404_brown.html) [[A]](http://www.ibm.com/developerworks/websphere/techjournal/1404_brown/1404_brown.html)
* Does unity of design imply an aristocracy of architects? Putting it simple: can good design emerge from a collective effort of all developers?
* What's the difference between design, architecture, functionality and aesthetic? Discuss. [[A]](http://stackoverflow.com/questions/704855/software-design-vs-software-architecture)
