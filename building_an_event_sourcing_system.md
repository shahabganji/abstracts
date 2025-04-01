## Building your own Event Sourcing System With Azure Cosmos DB

Event sourcing and Event-Driven Architectures are great ways to scale your system bringing scalability, elasticity,
and resilience within today's software systems. Azure Cosmos DB is a globally distributed, multi-model and scalable
database.

In this session, we will learn and examine the intrinsic details of Event Sourcing and how we could leverage Azure
Cosmos DB to achieve it. We will examine how to store events, getting states back, creating read models to satisfy
queries, and how to propagate necessary data in near real time, as events are happening, to other parts of the system.


--- 

Traditionally storing data not only causes loss of important facts in the past, but it is not close to the business.
Event sourcing enables us to record facts and travel in time to see what has happened in our system.

If you are wondering what it is or considering it as a complicated pattern to apply in practice, in this session I will
break it down in simple terms. Describing what is event sourcing, showing why to use it and what are the benefits. I
will describe the pillars of event sourcing, like commands, read models, projectors and the practical patterns you need
to know.

We will even go an extra mile, and I will show you how I used Azure Cosmos DB to implement an event-sourced system.


---

# General

### Rebuilding the Past: A Practical Guide to Event Sourcing

### Turning Facts Into Code: How Event Sourcing Aligns with Business Reality

Storing only the latest state of data can limit our ability to fully understand how a system evolved over time. Event
Sourcing changes this by capturing every meaningful change as a series of events, allowing us to reconstruct history,
audit past decisions, and align our software closely with business processes.

In this talk, we will demystify Event Sourcing by breaking it down into its core principles and practical applications.
You’ll learn when and why to use it, how it differs from traditional storage approaches, and how to overcome common
challenges. We’ll explore the foundational building blocks—commands, event stores, read models, and projectors—that make
Event Sourcing both powerful and approachable.

Finally, I’ll share real-world insights from implementing Event Sourcing using Azure Cosmos DB, showcasing how this
approach can bring scalability and reliability to modern distributed applications. ~~Whether you’re new to Event
Sourcing
or looking to deepen your understanding, this session will equip you with the knowledge to start building event-driven
systems with confidence.~~

---

# Øredev

### Event Sourcing Without the Headache: A Practical Deep Dive

Traditional data storage is like a Polaroid picture—it captures only a snapshot in time. But businesses need more than
just a static image; they need the full story. Event Sourcing provides a powerful alternative by recording every change
as an immutable event, allowing us to reconstruct history, analyze trends, and create robust, audit-friendly systems.

This session will explore the building blocks of Event Sourcing, breaking down concepts like event stores, commands,
read models, and projections. We’ll discuss practical implementation strategies, including how to leverage Azure Cosmos
DB for scalable event-sourced applications in .NET.

Whether you’re building microservices, working with distributed systems, or simply curious about Event Sourcing, this
talk will give you the tools and knowledge to get started with confidence.

---

# Techorama

~~The Power of the Past: Unlocking Business Insights with Event Sourcing, From State to Events: Rethinking Data Storage
in .NET, Event Sourcing Demystified: Practical Patterns for Real-World Systems~~

### Understanding Event Sourcing: What, When and How to Use It

In a world where businesses demand real-time insights and traceability, traditional data storage falls short. By storing
only the latest state, we lose valuable insights about past decisions. Event Sourcing offers a paradigm shift by
treating every state change as an immutable event, preserving business history and enabling new possibilities like
auditing, debugging, and machine learning insights.

In this session, we’ll break down Event Sourcing into its fundamental concepts—commands, events, event store, read
models, and
projectors—helping you understand how and when to apply it effectively. You’ll also see a real-world implementation
using Azure Cosmos DB, demonstrating how to build scalable event-sourced applications in .NET.

If you’ve ever been curious about Event Sourcing but found it too complex, this talk will give you the clarity and
confidence to start leveraging it in your own projects.


--- 

# NDC

### Rewriting History: A Practical Approach to Event Sourcing in .NET

### Think in Events: The Missing Piece in Scalable Systems

### Event Sourcing in Action: From Fundamentals to Cosmos DB

What if your database didn’t just store the current state of your data but remembered every change that led to it? Event
Sourcing provides a way to capture business events as they happen, enabling full traceability, better debugging, and
even predictive analytics.

In this talk, we’ll walk through the essentials of Event Sourcing—why it’s useful, how it works, and the patterns that
make it scalable. You’ll learn about its foundational components like commands, events, event stores, read models, and
projectors, and we’ll discuss real-world examples, including an implementation using Azure Cosmos DB.

By the end of this session, you’ll have a clear understanding of when to use Event Sourcing, and the trade-offs to
consider.


---

Living at the moment is great… until the moment throws a production error and your logs say: ¯\_(ツ)_/¯

Traditional systems forget the past. Event Sourcing doesn’t. It captures every change like a journal, making debugging,
audits, and insights way easier—and sometimes even fun. And it doesn’t just give you those benefits—it brings context to
your moment, something that matters not just in software, but in life too.

That’s exactly what I’ll be exploring in my talk at CodeCrafts Conference 2025 in Vienna: “Demystifying Event Sourcing:
A Practical Approach.”

🧩 We’ll walk through the core concepts—commands, events, read models, projectors, event store—and see how they come
together in a real-world application. And yes, there will be live coding, because there’s nothing like seeing it all
unfold in action.

🧠 If you’ve ever been curious about Event Sourcing but found it a bit intimidating, this session is for you. It’s all
about clarity, practical insights, and maybe a few dad jokes along the way. 😄
