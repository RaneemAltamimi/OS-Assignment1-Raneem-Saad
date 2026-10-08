# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
<<<<<<< HEAD
| **Full Name** | [Raneem saad aitamimi] |
| **Student ID** | [445052093] |
| **University Email** | 445052093@std.psau.edu.sa |
| **GitHub Username** | [RaneemAltamimi] |
| **Repository Link** | [Paste your repository link here] |
=======
| **Full Name** | [Raneem Saad Altamimi] |
| **Student ID** | [445052093] |
| **University Email** | 445052093@std.psau.edu.sa |
| **GitHub Username** | [RaneemAltamimi] |
| **Repository Link** | https://github.com/RaneemAltamimi/OS-Assignment1-Raneem-Saad |
>>>>>>> 3774e341ee761f476c947167aeb7d9ad0bfe60fb
 
---

## 🎥 Video Link

**Video Link**: https://drive.google.com/file/d/1JjtfMME-Tk-4XLVZ8s9f_6EDFXBpkIeu/view?usp=drivesdk

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log
### Entry 1 - [October 3, 2026, 8:00 PM]

**What I did**: Set up my student ID and prepared the project.

**Details**:
- Updated my student ID in `SchedulerSimulation.java`.
- Checked the project files and GitHub repository.
- Ran the original program to make sure it worked correctly.
- Committed and pushed the student ID changes.

**Challenges**: I needed to make sure that my student ID was entered correctly and that the original program still worked after the change.

**Solution**: I checked the code and ran the program to verify that the student ID and the original functionality were working correctly.

**Time spent**: 2 hours

---
### Entry 2 - [October 4, 2026, 6:00 PM]

**What I did**: Added the process priority feature.

**Details**:
- Added a priority value from 1 to 5 for each process.
- Generated the priority randomly for each process.
- Displayed the process priority when it entered the ready queue.
- Tested the program and checked the output.
- Committed and pushed the Feature 1 changes.

**Challenges**: I needed to understand where the priority should be stored and where it should be displayed in the ready queue.

**Solution**: I added the priority to the `Process` class and displayed it when the process was added to the ready queue. I then ran the program to check the result.

**Time spent**: 2 hours
---
### Entry 3 - [October 4, 2026, 7:00 PM]

**What I did**: Added the context switch counter feature.

**Details**:
- Added a static counter to store the total number of context switches.
- Incremented the counter each time a process started running.
- Displayed the total number of context switches after all processes completed.
- Ran the program and checked the output.
- The program displayed a total context switch count.
- Committed and pushed the Feature 2 changes.

**Challenges**: I needed to identify the correct place to increase the counter when a process starts running.

**Solution**: I placed the counter increment before `currentThread.start()` and tested the program to make sure the total was displayed correctly.

**Time spent**: 1 hour

---
### Entry 4 - [October 4, 2026, 8:00 PM]

**What I did**: Added the waiting time tracking feature.

**Details**:
- Added variables to track the process creation time and waiting time.
- Recorded the time when a process entered the ready queue.
- Calculated the waiting time using `System.currentTimeMillis()`.
- Added the waiting time to the process when it started running.
- Added a summary showing the process name, burst time, and waiting time.
- Ran the program and checked the output.

**Challenges**: I had an error when adding the method for recording the ready queue entry time.

**Solution**: I checked the location of the new method and corrected the brackets and code placement. After that, I ran the program again to verify that the code compiled correctly.

**Time spent**: 2 hours

---
### Entry 5 - [October 4, 2026, 11:00 PM]

**What I did**: Tested the complete program after adding all three features.

**Details**:
- Ran the program and checked the process priority output.
- Checked that context switches were counted correctly.
- Checked the waiting time calculations and summary table.
- Reviewed the code to make sure the original functionality was still working.

**Challenges**: I needed to make sure that the three new features worked together without affecting the original Round-Robin scheduling.

**Solution**: I ran the program several times and checked the output of each feature carefully.

**Time spent**: 2.5 hours
---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.
## Development Log Summary

**Total time spent**: Approximately 12 hours

**Most challenging part**: The most challenging part was implementing the waiting time feature because I needed to track when each process entered the ready queue and calculate how long it waited before running.

**Most interesting part**: The most interesting part was adding process priorities and seeing the priority information displayed when processes entered the ready queue.

**What I would do differently next time**: Next time, I would plan the implementation and testing of each feature more carefully before starting the coding. I would also test each feature separately more systematically before combining all the features.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:Through this assignment, I learned how multithreading works in Java and how threads can be used to simulate process scheduling. I learned that the Process class implements Runnable, and a thread is created using new Thread(process) inside addProcessToQueue(). I understood that Thread.start() starts the thread, while Thread.join() makes the scheduler thread wait until the process thread finishes its current execution. I also learned that Thread.sleep() is used inside the run() method to simulate a process using the CPU for a period of time. When a process does not finish within its time quantum, it can be added back to the ready queue. This helped me understand the relationship between threads, the ready queue, the time quantum, and Round-Robin scheduling.


## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was implementing the waiting time feature. I had to understand when a process entered the ready queue and when it started running to calculate its waiting time. I used the lastWaitingStart variable to record the time when a process started waiting. I also used the startWaiting() method to update the waiting start time when a process was added to the ready queue. In the run() method, I used System.currentTimeMillis() to calculate the time the process had waited. Testing the program helped me understand how waiting time could be tracked while keeping the original scheduling behavior.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame the challenges by working on each feature separately instead of adding all the changes at once. After implementing each feature, I ran the program and checked the output to see whether it worked correctly. When I worked on the waiting time feature, I reviewed how processes moved through the ready queue. I checked how startWaiting() and lastWaitingStart were used to track waiting time. I also checked the process summary table to see the calculated values. Testing each change helped me find mistakes and understand the code more clearly..]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading can be used in a web browser to handle tasks such as loading pages, downloading files, and responding to user actions. A mobile application can use separate threads for network requests while keeping the user interface responsive. In a game, different threads can help handle background tasks while the user continues playing. This is related to my assignment because each simulated process is executed by a Java thread. The ready queue and time quantum in my simulation demonstrate how CPU time can be shared among tasks. These examples helped me understand how multithreading can allow multiple tasks to make progress and improve application responsiveness.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is a program in execution that has its own memory and system resources, while a thread is a smaller unit of execution within a process. Separate processes generally require more resources to create and manage, while threads within the same process can share memory and resources. In this assignment, the Process class represents a simulated process, while new Thread(process) inside addProcessToQueue() creates a real Java thread to execute it. We used threads because they are suitable for simulating multiple tasks that share resources and need to take turns executing. This approach also makes it easier to demonstrate scheduling and context switching in the program.
]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*
Your Answer:
When a process does not finish within its time quantum, it gives up the CPU and is placed at the end of the ready queue. In my output, P9 had a burst time of 8356ms and the time quantum was 4000ms, so it could not finish in one turn. P9 was re-queued two times before it finished, first with 4356ms remaining and then with 356ms remaining. It then executed for the final 356ms and finished. Re-queuing is important because it allows other processes to use the CPU and prevents one process from using the CPU continuously, which provides fairness.

Example from my output:

P9 executing quantum [4000ms]
P9 completed quantum 4000ms
Remaining time: 4356ms
P9 yields CPU for context switch

P9 (Priority: 1) added to ready queue

Later in the output:

P9 executing quantum [4000ms]
P9 completed quantum 4000ms
Remaining time: 356ms
P9 yields CPU for context switch

P9 (Priority: 1) added to ready queue

Finally:

P9 executing quantum [356ms]
P9 completed quantum 356ms
Remaining time: 0ms
P9 finished execution!

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*
New: P1 is in the New state when its Thread object is created using new Thread(process) inside addProcessToQueue(), before start() is called. Runnable: P1 becomes eligible to run when the scheduler calls currentThread.start().
Running: P1 executes its run() method when the Java thread is scheduled and begins using its time quantum.
Waiting: P1's thread enters the Timed Waiting state when Thread.sleep() is called, while the main scheduler thread waits for P1 when it calls currentThread.join().
Terminated: P1 reaches the Terminated state when its run() method finishes; in my output, P1 first had 656ms remaining and later completed its final execution.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?
Example 1: Operating-system CPU scheduling

An operating system can use Round-Robin scheduling to share CPU time among multiple processes or threads. Each process receives a fixed time quantum, and an unfinished process returns to the ready queue. This provides fairness because each process gets a turn to use the CPU. The time quantum limits how long a process can run in one turn, and a context switch allows another process to run. This is similar to my simulation, where processes take turns using a 4000ms time quantum.

Example 2: Web server request handling

A web server can use multiple threads to handle requests from different users. When many CPU-intensive requests need processing, scheduling can help share CPU time among the tasks. Round-Robin scheduling can provide fairness by allowing each task a limited amount of execution time before another task gets a turn. In this example, requests represent the tasks, the time quantum limits each turn, and context switching allows execution to move between threads. This is related to my simulation because unfinished processes return to the ready queue instead of using the CPU continuously.

## Summary
Summary

Key concepts I understood through these questions:

I understood how Round-Robin scheduling uses a time quantum and Ready Queue to give processes fair CPU time.
I understood how threads move through different lifecycle states using methods such as Thread.start(), Thread.sleep(), and Thread.join().
I understood how re-queuing and context switching allow multiple processes to make progress without one process continuously using the CPU.

Concepts I need to study more:

I need to study more about the difference between a Java thread's actual states and the simplified thread lifecycle states used when explaining scheduling.
I need to study more about how real operating systems perform context switching and CPU scheduling internally.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.

