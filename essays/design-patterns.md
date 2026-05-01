---
layout: essay
type: essay
title: "Why Design Patterns Are Basically a Playbook for Coding"
# All dates must be YYYY-MM-DD format!
date: 2026-04-30
published: true
labels:
  - Design
  - Bootstrap
  - NextJs
---

<img width="200px" class="rounded float-start pe-4 img-fluid" src="../img/final-project-proposal/sports-playbook2.avif" alt="Sports playbook with drawn plays and coding elements">


# Why Design Patterns Are Basically a Playbook for Coding

If you’ve ever played on a sports team, you know the value of a good playbook. It’s not just a collection of random moves, it’s the shared language and strategy that helps a team work together, adapt to challenges, and win games. Building software, as I’ve learned while working on **Manoa Course Wise**, is surprisingly similar. You can try to wing it, but you’ll quickly find yourself in trouble. That’s where design patterns come in. You can think of them like the playbook of software development.

## What Exactly Are Design Patterns?

So, what exactly are design patterns? Think of them as the tried and true plays that coaches and players have developed over years of experience. They’re not strict rules, but more like best practices. ways to solve common problems that pop up again and again. In football, you might have a go-to passing play for third down. In software, you might use the **Component** pattern to build a user interface out of reusable pieces. Both make life easier, help you avoid mistakes, and let you focus on the bigger picture.

When my team and I started building **Manoa Course Wise**, we didn’t have all the answers. But we did have a playbook. For our user interface, we leaned heavily on the **Component** pattern. Every part of our app, from the Navbar to the CourseCard, is its own little player, ready to be called into action wherever needed. This made our code cleaner and let us build new features faster, since we could just reuse components instead of reinventing the wheel every time.

## Key Patterns We Used in Manoa Course Wise

Handling data was another area where the playbook came in handy. We used the **Repository** pattern, which is kind of like having a solid defensive line. Instead of letting every part of the app poke around in the database (which would be a mess), we set up a single, organized way to handle data. This kept things secure and made it way easier to update or change how we store information down the road.

User actions, like submitting a review,  were another challenge. Here, we used the **Command** pattern. Each action is wrapped up in its own little package, so we can validate it, undo it, or log it if something goes wrong. It’s like calling a timeout in a game to review what just happened and make adjustments.

We also found ourselves using the **Container-Presenter** pattern, which helped us keep our code organized by separating the logic (the “coach”) from the presentation (the “players on the field”). And for things like our database connection, I believe we used the **Singleton** pattern to make sure we only had one instance running. No need for extra players crowding the field!

## The Bigger Picture

Looking back, I realize that design patterns didn’t just help us write better code, they helped us work better as a team. We had a shared language and strategy, which made it easier to collaborate, review each other’s work, and build something we’re all proud of. And just like in sports, having a playbook didn’t mean we couldn’t improvise or try new things. It just gave us a solid foundation to build on.

So, if you’re ever asked in an interview, “What are design patterns?” or “Which ones have you used?” — think about your favorite sport. Every great team has a playbook, and every great software project relies on design patterns. For **Manoa Course Wise**Our playbook made all the difference
