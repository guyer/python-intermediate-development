---
title: "Setting the Scene For the Workshop"
start: false
colour: "#FBED65"
teaching: 15
exercises: 0
questions:
- "What are we teaching in this course?"
- "Why did we pick specific topics to cover?"
objectives:
- "Setting the scene and expectations"
- "Making sure everyone has all the necessary software installed"
keypoints:
- "This lesson focuses on core, intermediate skills covering the whole software development life-cycle
  that will be of most use to anyone working collaboratively on code."
- "For code development in teams - you need more than just the right tools and languages. You need a strategy
  (best practices) for how you'll use these tools as a team."
- "The lesson follows on from the novice Software Carpentry lesson, but this is not a prerequisite for
  attending as long as you have some basic Python, command line and Git skills and you have been using them for a
  while to write code to help with your work."
---

## Introduction
So, you have gained basic software development skills either by self-learning or attending, e.g., a [novice Software
Carpentry course][swc-lessons]. You have been applying those skills for a while by writing code to help with your work
and you feel comfortable developing code and troubleshooting problems. However, your software
has now reached a point where there’s too much code to be kept in one script. Perhaps it's involving more
researchers (developers) and users, and more collaborative development effort is needed to add new functionality
while ensuring previous development efforts remain functional and maintainable.

This course provides the next step in software development - it teaches some **intermediate software
engineering skills and best practices** to help you restructure existing and design more robust,
reusable and maintainable code, automate the process of testing and verifying software correctness and
support collaborations with others in a way that mimics a typical software development process
within a team. The course uses a number of different **software development tools and techniques**
interchangeably as you would in a real life. We had to make some choices about
topics and tools to teach here - based on ease of installation for the audience, length of the course
and other considerations. Tools used here are not mandated though - alternatives exist and
we point them out along the way.
Over time, you will develop a preference for certain tools and programming languages based on your
personal taste or based on what is commonly used by your group, collaborators or community.
However, the topics covered should give you a solid foundation for working on software development
in a team and producing high quality software that is easier to use, develop,
and sustain in the future by yourself and others, and skills and tools
taught here, while Python-specific, are transferable to other similar tools and programming languages.

The course is organised into the following
four sections:

![Course overview diagram](../fig/course-overview.png){: .image-with-shadow width="800px" }

### Section 1: Setting up Software Environment
In the first section we are going to set up our working environment and familiarise ourselves with various tools and techniques for
software development in a typical collaborative code development cycle:
- **Integrated Development Environment (IDE)** for **code development, testing and debugging**,
- **command line** for running code and interacting with the **command line tool Git** for
  **version control** and branching the code out for developing new features in parallel,
- **GitHub** (central and remote source code management platform supporting version control with Git)
  for **code backup, sharing and collaborative development**,
- **virtual environments** for **isolating a project** from other projects developed on the same machine, and
- **Python code style guidelines** to make sure our code is
  **documented, readable and consistently formatted**.

### Section 2:  Verifying Software Correctness at Scale
Once we know our way around different code development tools, techniques and conventions, in the second section we learn:
- how to set up a **test framework** and write tests to verify the correct behaviour of the code, and
- how to automate and scale testing with **Continuous Integration (CI)** using
  **GitHub Actions** (a CI service available on GitHub).

### Section 3: Designing Software Architecture
In this section, we step away from writing code for a bit to look into different **software design paradigms**
to understand the wider landscape in which you can design software and to help you with the
design decisions you have to make. Each paradigm represents a slightly different way of thinking about and structuring
the code and each has certain strengths and weaknesses when used to solve particular types of problems -
useful to know so you can recognise where it might be useful to switch in your own code.

### Section 4: Improving and Managing Software Over its Lifetime
Finally, we are back to practical applications and learning to **publish and release
software for reuse** by others and how to manage software improvements from feedback through
agile techniques. You will work with your fellow learners on a group project (as you would do when
collaborating on a software project in a team) and we will address best practices in **documenting**, **licencing**, **tracking issues**, and **supporting your software**.

## Before We Start

A few notes before we start.

> ## Prerequisite Knowledge
> This is an intermediate-level software development course intended for people who have already been developing code in
> Python (or other languages), e.g. for at least a few months, and applying it to their own problems
> after gaining basic software development skills.
> So, it is expected for you to have some prerequisite knowledge on the topics covered, as outlined at the [beginning of the lesson](/index.html#prerequisites).
Check out this [quiz](../quiz/index.html) to help you test your prior knowledge and determine if this course is for you.
{: .callout}

> ## Required Software
Please make sure that you have all the necessary software installed as described in the [Setup](../setup.html) section.
This section also contains instructions on how to test your setup.
{: .callout}

> ## Compulsory and Optional Exercises
Exercises are a crucial part of this course and the narrative. They are used to reinforce the points taught and give
you an opportunity to practice things on your own. Please do not be tempted to skip exercises as that will get your
local software project out of sync with the course and break the narrative. Exercises that are clearly marked
as "optional" can be skipped without breaking things but we advise you to go through them too, if time allows.
All exercises contain solutions but, wherever possible, try and work out a solution on your own.
{: .callout}

> ## Outdated Screenshots
> Throughout this lesson we will make use and show content from Graphical User Interface (GUI) tools (PyCharm and GitHub).
> These are evolving tools and platforms, always adding new features and new visual elements.
> Screenshots in the lesson may then become out-of-sync, refer to or show content that no longer exists or is different to
> what you see on your machine. If during the lesson you find screenshots that no longer match what you see or have
> a big discrepancy with what you see, please [open an issue](https://github.com/softwaresaved/python-intermediate-development/issues/new) describing what you see and how it differs from the lesson
> content. Feel free to add as many screenshots as necessary to clarify the issue.
{: .callout}

{% include links.md %}
