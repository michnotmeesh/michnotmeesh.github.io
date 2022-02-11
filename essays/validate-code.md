---
layout: essay
type: essay
title: Why Your ICS TA Took So Long to Grade
# All dates must be YYYY-MM-DD format!
date: 2022-02-09
labels:
  - eslint
  - intellij
  - coding standards
---

This is my formal apology to all previous ICS TAs for having to read my code before I learned about coding standards and code validating tools (No wonder it always took _forever_ to grade our homework). After this module, my biggest takeaway was realizing how following coding standards does so much more than changing the format of your code.

## As a Learner

I felt quite intimidated the first time setting up IntelliJ, ESLint, and GitHub. There were many instructions and I ran into many issues with the setup alone. However, starting is the first step and these tools make coding a whole lot easier.

### ESLint

<div>
<img class="ui image medium centered" src="../images/eslint-meme.jpeg">
</div>
  
ESLint helped my code become more readable and well-structured, but there was definitely a learning curve. It was a bit frustrating to suddenly have so many warnings and red underlines appear. It was especially annoying when the errors were for the tiniest _mistakes_. Like, will the program really not run if I don't delete those trailing spaces? It shouldn't be a big deal.

However, receiving those errors and taking the time to fix them was very helpful because it taught me what not to do next time. As I practiced more and more with ESLint running, fewer and fewer errors appeared, and doing it the new way started to grow on me. That's the beauty of making mistakes: you learn something from them and adapt to become better.

When I code now, I have two priorities. The first priority is to focus on writing each function and getting the program to run as expected. I ignore all of the ESLint errors because most of them are quick fixes for readability purposes. When the program runs as I want it to, then I move on to the next priority: making the code readable. This is when I focus on the ESLint errors. When I'm done correcting all of the errors, I take a look at my code and think "This **does** look so much better!"

ESLint makes it easier to search and debug any code. In other ICS classes, it would take hours and hours and hours to find a missing semicolon or missing curly bracket because it was just so messy and illegible. Although not every ESLint error message is specific or helpful, it is definitely an upgrade from what we had to do in the previous years.

### GitHub and git

<div>
<img class="ui image medium centered" src="../images/github.jpeg">
</div>

Git is basically the ultimate redo button and GitHub is the log that keeps all the old changes. I haven't used the individual commits, fetch, or branches in a practical way just yet, but I can see how useful it would be when working on a bigger project with multiple developers. I also really appreciate how each commit distinguishes changes; green for additions, yellow for modifications, and red for deletion. Each commits even logs who made the changes.

## As a Developer

<div>
<img class="ui image large centered" src="../images/laulima_full_banner.jpeg">
</div>

GitHub and git are extremely powerful; it's inspiring. While exploring GitHub, I was thinking about how easier it would be if all of our coding assignments were done through GitHub. In other words, I was trying to find a way to get rid of Laulima (because it really does suck).

Here is my _general_ idea for using git and GitHub to handle coding assignments:
1. Instructor creates a private repository for the assignment, which includes instructions, expectations, and/or possibly starter code
2. Students get invited and clone the repository onto their local computer. When working on the assignment, students are allowed to make as many commits as they need.
3. To turn in the assignment, students push their repository onto another repository specifically for turning in assignments
4. When it is past the due date, the instructor makes the repository private and submissions are no longer accepted

This is not a complete idea, but I strongly believe that something like GitHub can be modified to support distributing and collecting assignments in a secure and easy way. Laulima is not the best fit for ICS assignments. I even think grading is better done through GitHub because the TA would see **exactly** what the student sees. If configured to do so, GitHub could possibly handle line-by-line feedback and it would be a better UI for students to see the specific lines where mistakes were made (rather than a single feedback box on Laulima). If there is a way to make the need for Laulima obsolete, I'm all for it.

## Looking Forward
Growth is realizing that your code is no longer just for your own reference. Utilizing coding standards introduced a crucial part of software engineering: teamwork. Although we have not started any group work, this week provided resources and solid expectations for how group work can be done effectively.


_If you have the time, shoot your former TAs an email thanking them for even attempting to read your mess of code._
