---
layout: article
date:   2021-08-05
title:  Xierumeng's Guide to Policy 71
note:   This is based on my experience. Better to err on the side of caution.
categories: guide
permalink: /resources/policy-71-guide
---
Policy 71 is academic integrity. Basically don't cheat. But what does that actually mean?

# Collaboration

![Meme: Can I copy your answers? Yeah just change it up a bit. Photo of barely a change.](https://i.kym-cdn.com/photos/images/original/001/208/115/7e1.png)

Basically, collaboration is considered as cheating. But to what degree is student cooperation allowed?

**Discussion of high-level assignment concepts: Okay.**

* Example: "In the linked list destructor you should keep calling popHead to pop all of the nodes."

**Discussion of provided materials: Okay.**

* Example: "Can you help me understand what's happening in the linked list from last lecture?"

**Discussion of specific concepts: Questionable.**

* Example: "Did you remember to set your head pointer to null when the list is empty? Maybe that's what's causing the crash."

**Viewing and/or sharing code snippets/diagrams/partial answers/specific formulas/partial output: Very questionable.**

* Example: "I put a bunch of printfs in the pushHead method, here's what came out, I can't figure out what's wrong, can you help?"

**Viewing and/or sharing the entire project/assignment answer for a question/design process: Bad.**

* Example: "Here's my linked list code, can you help me debug?"

* Even viewing is bad because it pollutes your mind with a possible solution (or optimization/correction if you've already written a solution).

# Copying

**Actively copying from an external source and giving a full citation: Okay.**

* Usually done for papers rather than code or assignments.

**Actively copying from an external source while giving the minimum effort to cite: Possibly okay**

* Example: For a cURL multithreading assignment, I copied an implementation from IBM, changed it up a bit, and put the code and link in my submission.
```cpp
        ...
        // Lots of code I wrote myself above

        // Loop over all sockets that have returned something interesting
        // Code adapted from: [IBM link]
        // This code is in ibm-example.c
        for (int i = 0; i < pollSocketsSize; i++)
        {
            // IBM code that I modified
            ...
        }

        // Lots more code I wrote myself below
        ...
```

**Actively copying from an external source and not citing: Really bad.**

* This is called "passing your work as someone else's" AKA plagiarism, which universities *really hate*.

**Actively copying from an external source when you're not supposed to: Bad.**

* Example: Any assessment where it's not allowed (tests, exams, etc.).

**Actively copying an answer for this specific assignment/question/project from someone else: Bad.**

* Examples:
    * Someone else in the class.
    * Chegg or other locations where solutions were posted.
    * Someone who took this course/similar course previously.
    * YOURSELF if you're retaking the course (yes, you can be dinged for plagiarizing your own work!).

**Actively copying someone else in an examination: Really bad.**

* Don't.

# Misuse of Resoruces

Basically, the computer equipment and software owned by the university is for education.

**For a course you're taking: Okay.**

* That's why it's there.

**For a student design team: Okay.**

**For a Docker image(?) for your webserver you're testing: Possibly okay.**

* It's still for your own education, right?

**Your web server is production trying to serve a million requests: Bad.**

* Be mindful that other people are trying to use the computers too.

**Mining cryptocurrency: Really bad.**

* A CS student apparently did this and then got banned from all of the computers on campus forever (a long time!). Given that those computers are required to test and submit code assignments, this is not ideal.

**Accidents such as program exploding out of control: Possibly okay.**

* As safety officer for a student design team, I say: Don't have accidents ez.

    * You can make mistakes but try not to repeat them please.

    * Example: Multiprocessor program accidental fork bomb.

**Deliberate sabotage: Really bad.**

* Probably ban. Suspension/expulsion possible. Maybe even legal action.
* This would fall under a non-academic policy 71 offence.

**Reimbursement of funds for a student design team: Okay.**

**Falsifying a reimbursement to get free money: Really bad.**

* And this is why I have to through so much documentation to get money back for shipping a small piece of equipment from Waterloo to a team member in Toronto.

# Other

All of the "bad" behaviour: cyberbullying, harrassment, threats, etc.

Breaking the law. Just don't. Even worse if it occurred on campus.

# External Resources

* [UW official policy 71](https://uwaterloo.ca/secretariat/policies-procedures-guidelines/policy-71)
* [Academic integrity tutorial](https://uwaterloo.ca/library/research-supports/academic-integrity/academic-integrity-tutorial)
* [Douglas Harder's advice if you are accused of policy 71](https://ece.uwaterloo.ca/~dwharder/Policy71/). You can also contact WUSA for help.
* [Douglas Harder video on cheating](https://www.youtube.com/watch?v=Wm5eLTeC9KM)
* [Summary lists of previous years' academic offences and penalties (right bar)](https://uwaterloo.ca/secretariat/committees-and-councils/university-committee-student-appeals)
