# 📝 Today I Learned (TIL)

> "The more I learn, the more I realize how much I don't know." — Albert Einstein

## 🚀 About This Repository
This is a collection of concise write-ups on small things I learn day-to-day across my software engineering journey. These are not full blog posts, but rather "atomic" notes—short, focused explanations of concepts, syntax, or bug fixes that I want to retain.

I created this repository to:
1.  **Solidify Knowledge:** Writing it down helps me understand it better.
2.  **Track Progress:** A history of my growth as a developer.
3.  **Share Value:** If it helped me, it might help someone else.

## 📂 Categories
I organize my learnings by topic. You can browse the directories above, but here are the main areas I focus on:

* **Backend & APIs:** (e.g., REST, Authentication, Performance tuning)
* **Architecture:** (e.g., Design Patterns, Clean Architecture, Microservices)
* **Database:** (e.g., SQL optimization, EF Core, NoSQL)
* **DevOps & Tools:** (e.g., Docker, CI/CD, Git)
* **Languages:** (e.g., C#, JavaScript)

## 💡 Example of a TIL
*An example of how I document a learning:*

### [Issue: Why use `IQueryable` vs `IEnumerable`?]
**The Concept:** `IEnumerable` pulls all data into memory before filtering (client-side evaluation), while `IQueryable` executes the filter in the database (server-side evaluation).
**When to use:** Always use `IQueryable` when building database queries to ensure SQL is generated efficiently.

---

## 📈 Recent Learnings
*(I update this list automatically or manually periodically)*

* [Added note on Dependency Injection Lifetimes](./Backend/DI-Lifetimes.md)
* [Solved a CORS issue in Localhost](./Web/CORS-Fix.md)
* [Understanding Indexing strategies](./Database/Indexing.md)

---

*This repository is inspired by the "TIL" movement in the open-source community.*
