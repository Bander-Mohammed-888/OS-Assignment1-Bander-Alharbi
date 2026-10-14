<img width="1092" height="363" alt="image" src="https://github.com/user-attachments/assets/773fe5db-25e9-4315-a507-6ba0cb8f6b4c" /># 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

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
| **Full Name** | [Bander Mohammed Alharbi] |
| **Student ID** | [446050832] |
| **University Email** | [446050832]@std.psau.edu.sa |
| **GitHub Username** | [Bander-Mohammed-888] |
| **Repository Link** | [https://github.com/Bander-Mohammed-888/OS-Assignment1-Bander-Alharbi] |
 
---

## 🎥 Video Link

**Video Link**: https://youtu.be/QLC7cDtvyRg?si=iyY8BAQEuww8dZhF

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

### Entry 1 - [October 9, 2026, 11:05 AM]
**What I did**:Set up the project and configured my student ID.

**Details**:
- Opened the starter project in VS Code.
- Renamed the repository to OS-Assignment1-Bander-Alharbi.
- Set my student ID to 446050832 in SchedulerSimulation.java.
- Reviewed the project structure and the existing scheduling code.
- Committed and pushed: Update student ID for random number generation.

**Challenges**: Understanding the existing project structure and how the scheduler manages processes and threads.

**Solution**: Reviewed the Java classes and followed the program flow before implementing the new features.

**Time spent**:  Approximately 1 hour.

---

### Entry 2 - [October 9, 2026, 7:06 PM]
**What I did**:Implemented process priority

**Details**:
- Added the priority field to the Process class.
- Generated priorities from 1 to 10.
- Displayed priority when a process entered the ready queue.
- Kept priority as display and tracking information without changing FIFO order.
- Committed using Feature 1: Add process priority.

**Challenges**:Displaying priority without changing the original scheduling order.

**Solution**:Stored priority separately and displayed it when adding the process to the queue.

**Time spent**: Approximately 2 hours.



---

### Entry 3 - [October 9, 2026, 8:50 PM]
**What I did**:Implemented the context-switch counter.

**Details**:
- Added the static contextSwitchCount variable.
- Incremented it before currentThread.start().
- Printed the total after the scheduler finished.
- Committed using Feature 2: Add context switch counter.

**Challenges**:Deciding where the counter should be incremented.

**Solution**:Incremented it immediately before starting each scheduled thread.

**Time spent**: Approximately 2 hours.

---

### Entry 4 - [October 10, 2026, 12:30 PM]
**What I did**:Implemented waiting-time tracking.

**Details**:
- Added readySince and waitingTime to Process.
- Added markReady() and recordWaitingTime().
- Added getTurnaroundTime().
- Displayed the final summary table.
- Committed using Feature 3: Waiting Time Tracking.

**Challenges**:Accumulating waiting time when a process returned to the ready queue.

**Solution**:Recorded the time when a process entered the queue and accumulated the elapsed waiting time before execution.

**Time spent**:Approximately 3 hours.

---

### Entry 5 - [October 10, 2026, 12:10 PM]
**What I did**:Tested the scheduling simulation.

**Details**:
- Ran the simulation with student ID 446050832.
- Checked the 14 processes and the 5000 ms time quantum.
- Reviewed priority messages and the context-switch counter.
- Checked the final waiting-time and turnaround-time table.

**Challenges**:Verifying that the three features worked together.

**Solution**:Compared the program output with the expected scheduling behavior and checked that all processes finished.

**Time spent**:Approximately 2 hours.

---

### Entry 6 - [October 10, 2026, 12:00 PM]
**What I did**:Reviewed the final implementation and commit history.

**Details**:
- Reviewed the student ID commit.
- Checked the commits for all three features.
- Reviewed the recorded output and prepared the documentation.
- Confirmed that the code commit history showed changes on October 9 and October 10.

**Challenges**:Making the documentation match the actual code and output.

**Solution**:Used the recorded GitHub commit messages and the program output as references.

**Time spent**:Approximately 1 hour.

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [ Approximately 11 hours.]

**Most challenging part**:
The most challenging part was implementing waiting-time tracking because a process can return to the ready queue multiple times. I had to make sure the waiting time was accumulated correctly without changing the Round-Robin scheduling order.

**Most interesting learning**:
The most interesting part was learning how Java threads work with the Round-Robin algorithm. I also learned how to add process priorities, count scheduled thread executions, and display waiting-time and turnaround-time summaries.

**What I would do differently next time**:
 I would test each feature immediately after implementing it, keep better notes during each work session, and document the results before moving to the next feature.
 
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

**Your Answer:** *(5-7 sentences)*

[I learned how Java threads can be used to simulate the execution of multiple processes. In my assignment, the Process class implements Runnable, and the scheduler creates a thread using new Thread(process). The start() method begins execution, while join() makes the scheduler wait until the current thread finishes its turn. The Thread.sleep() method simulates the time spent executing a process during its time quantum. I also learned how the FIFO ready queue works with the Round-Robin algorithm. One important lesson was that the simulated Process object is different from the Java Thread that executes its code.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part was implementing waiting-time tracking without changing the original Round-Robin scheduling behavior. A process can enter the ready queue more than once, so its waiting time must include every waiting interval. I needed to understand when a process entered the queue and when the scheduler selected it again. I also had to ensure that the final summary displayed the timing values for all processes. The challenge was recording waiting time at the correct points in the scheduling flow. This helped me understand how queue management and timing calculations work together.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame the challenges by reviewing the existing code and implementing the features one at a time. I first configured my student ID, then added process priority, the context-switch counter, and waiting-time tracking. I followed the scheduler's execution flow to decide where each change should be placed. After implementing the features, I ran the simulation and checked the priorities and final timing summary. My recorded output showed 14 processes, a 5000 ms time quantum, and a context-switch counter value of 22. Reviewing the results helped me understand how the new features worked with the original scheduler.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading concepts can be applied to operating systems, servers, and applications that handle several tasks. An operating system schedules runnable tasks so that they can share CPU time. A time quantum gives a task a limited opportunity to execute before another task gets a turn. A server can process requests from multiple clients while managing tasks that are waiting for CPU time. Waiting-time measurements can help developers understand how long tasks remain in a queue. These concepts help explain how scheduling can improve fairness and responsiveness when tasks compete for processing time.]

### Optional: What would you like to learn more about?

[I would like to learn more about thread synchronization, race conditions, and deadlocks. I also want to understand how different CPU scheduling algorithms compare with Round-Robin. Learning more about these topics would help me understand how operating systems manage concurrent tasks.]

### Optional: How confident do you feel about multithreading concepts now?

[Intermediate. I understand the basic roles of `Runnable`, `Thread.start()`, `Thread.join()`, and `Thread.sleep()`. I can explain how the FIFO ready queue and Round-Robin scheduling work in my simulation. I still need more practice with thread synchronization and advanced scheduling concepts.]

### Optional: Feedback on the assignment

[The assignment helped me connect operating-system concepts with Java programming. Implementing the three features made the scheduling process easier to understand. Reading the starter code was challenging at first, but running the program helped me follow its execution. The assignment also showed me the importance of testing code changes and documenting the development process.]

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

[In this assignment, the `Process` class is a simulated process that implements Java's `Runnable` interface, while a Java `Thread` executes its code. In `addProcessToQueue()`, the statement `new Thread(process)` creates a thread associated with the simulated process. Java threads in the same application generally share memory, while separate operating-system processes have separate address spaces and usually need inter-process communication to exchange data. Creating threads generally has less overhead than creating separate operating-system processes. We used threads to simulate process execution and scheduling without launching a separate operating-system process for every simulated process.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, a process that does not finish within its time quantum is added to the end of the ready queue when other processes are waiting. In my output, P1 had a burst time of 7608 ms and a time quantum of 5000 ms, leaving 2608 ms after its first turn. P1 was re-queued once and then completed its remaining execution. The ready queue followed FIFO order, so other waiting processes received their turns before P1 executed again. Re-queuing improves fairness because an unfinished process does not occupy the CPU for its entire burst time while other processes are waiting.]

Example from my output:
```
[P1 executing quantum [5000ms]
P1 completed quantum 5000ms
Remaining time: 2608ms
P1 yields CPU for context switch
P1 added to ready queue | Burst time: 7608ms | Priority: 2

P1 executing quantum [2608ms]
P1 completed quantum 2608ms
Remaining time: 0ms
P1 finished execution!]
```

**Explanation of example:**
[P1 first executes for 5000 ms but still has 2608 ms remaining. Because other processes are waiting, the scheduler adds P1 to the end of the ready queue. After the other processes receive their turns, P1 executes again for the remaining 2608 ms. P1 is therefore re-queued once after its initial execution turn before it finishes.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1's Java thread is created in addProcessToQueue() using new Thread(process), so it starts in the New state.]

2. **Runnable**: [When the scheduler calls currentThread.start(), P1's thread becomes eligible for execution by the JVM.]

3. **Running**: [When the JVM schedules P1's thread, its run() method executes the simulated process work and updates the remaining time.]

4. **Waiting**: [When P1 calls Thread.sleep(), its thread enters the TIMED_WAITING state. Separately, the scheduler's main thread waits for P1 to finish when it calls currentThread.join().]

5. **Terminated**: [P1's thread becomes terminated after its run() method finishes. If P1 still has work remaining, the program creates a new Thread object for the same simulated Process object.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling for Multiple Tasks]

**Description**:
[An operating system must share CPU time among multiple runnable tasks, such as applications and background services. Each runnable task plays a role similar to a process in my simulation. A time quantum limits how long a task can execute before the scheduler gives another task an opportunity to run. When execution switches from one task to another, the operating system performs a context switch. These operations help the operating system manage tasks that compete for CPU time.]

**Why Round-Robin works well here**:
[Round-Robin gives runnable tasks repeated turns instead of allowing one unfinished task to occupy the CPU indefinitely. A suitable time quantum helps balance fairness and responsiveness. In my simulation, P1 used 5000 ms in its first turn and then returned to the ready queue with 2608 ms remaining. This demonstrates how an unfinished task can wait while other tasks receive CPU time. Modern operating systems may use more advanced scheduling policies than simple Round-Robin.]

### Example 2: [A Server Handling Multiple Client Requests]

**Description**:
[A server may receive requests from multiple clients that need processing. Each request or runnable task can represent a unit of work competing for CPU time. A time quantum can limit how long a CPU-bound task executes before another runnable task receives an opportunity. Waiting-time measurements can help developers identify tasks that spend too long waiting for execution. This scenario is related to my simulation because unfinished tasks may need another turn before they complete.]

**Why Round-Robin works well here**:
[Round-Robin can distribute execution opportunities among runnable tasks and reduce the chance that one CPU-bound task monopolizes the processor. Re-queuing unfinished tasks gives other waiting tasks a chance to execute. A context switch allows the CPU to move from one runnable task to another. This can support fairness and responsiveness when many tasks compete for CPU time. Real servers may use different scheduling strategies depending on their workloads and performance requirements.]

## Summary

**Key concepts I understood through these questions:**
1. Java threads, the `Runnable` interface, and the roles of `start()`, `join()`, and `sleep()`.
2. Round-Robin scheduling, FIFO ready queues, time quantum, and re-queuing unfinished processes.
3. Process priority, context-switch counting, waiting-time tracking, and turnaround-time calculations.

**Concepts I need to study more:**
1. Thread synchronization, race conditions, and deadlocks.
2. Other CPU scheduling algorithms and how their performance compares with Round-Robin.
---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [X] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [X] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [X] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [X] Student ID is set in `SchedulerSimulation.java` (line 150)
- [X] Code compiles and runs with no errors
- [X] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [X] Each feature has clear comments

**Commits**
- [X] **At least 3 meaningful commits, ideally 6 or more**
- [X] **One commit per feature**
- [X] Commits are spread over **different dates** (not all in the last hour)
- [X] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [X] Full name and student ID filled in at the top
- [X] Development log has **5+ entries** on different dates
- [X] Reflection: 4 questions, 5-7 sentences each
- [X] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [X] No `[...]` placeholders left
- [X] No section headers deleted

**Video**
- [X] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [X] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [X] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [X] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
