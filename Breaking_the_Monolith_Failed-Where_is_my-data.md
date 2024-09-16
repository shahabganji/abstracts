## Breaking the Monolith Failed! Where is my data?

Applications start to become legacy at the point that their data model is not evolving anymore! Even though there are
countless books and articles describing how to manage and refactor the code base using patterns like Strangler Fig and
Branching by Abstraction, this session is about how to liberate your data model. A software without data is like a joke
without a punchline, leaves you hanging.

~~There's a myriad of complexity in breaking a monolith and modernize your products. There are countless books and
articles helping how we could gradually replace the old functionalities and code bases with new one. Patterns like
Strangler Fig, enables the software team to have control over how the old system will be finally shut down and the new
system seamlessly fulfill old and new requirements. However, the core part of every software system is the data behind
it. A software without data is like a joke without a punchline—leaves you hanging.~~

I’ve seen firsthand how crucial it is to have a robust plan for data migration, working on projects where we faced this
exact problem, the code migration was progressing smoothly, but our legacy data model held us back. It was a pivotal
moment that made me realize: without effectively addressing data migration, no amount of code refactoring or system
redesign would suffice. Since then, I’ve explored various approaches, experimenting with different patterns and tools to
tackle this challenge. While there are numerous approaches offering data integration between systems, whether it is a 
shared database or schema, to having separate data stores and implementing Change Data Capture using Debezium or Kafka, the 
real challenge is left to the reader; listen to your environment and choose which approach fits your situation better.
~~Being able to liberate the data in legacy applications and integrate them into the new systems is just as important as
changing the code base and how the components of system are organized; having a modern and flexible data model serving
the new requirements of the system requires to know how we could untangle our new design from the old model.~~

Throughout this session, we will examine different patterns that can be leveraged to liberate data in your system and
allow it to flow seamlessly. We will examine the advantages and disadvantages of each approach and discuss tools we
could employ to achieve this goal. By the end of this session, you will be better equipped to make informed decisions
about how to migrate and synchronize data in your software applications.
