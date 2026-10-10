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
| **Full Name** | [Wed Altamimi] |
| **Student ID** | [446052008] |
| **University Email** | [446052008]@std.psau.edu.sa |
| **GitHub Username** | [wedrtmai] |
| **Repository Link** | [https://github.com/wedrtmai/OS-Assignment1-Wed-Altamimi] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/drive/folders/18q-HfFZK_bg-s9ySA9irRHF43JvS0V9p]

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

### Entry 1 - [October 7, 2026 , 06:30 PM]
**What I did**:Forked the repository, set up the project locally, and updated the student ID.

**Details**:Forked the starter repository, set up the Java project locally in VS Code, and updated the student ID variable to initialize the random number generator

**Challenges**: Ensuring the random number generator is correctly seeded with my unique university ID so the simulation output is unique.

**Solution**:Located line 150 in SchedulerSimulation.java and replaced the default ID placeholder with my actual student ID before pushing the first commit

**Time spent**:30 minutes

---

### Entry 2 - [October 7, 2026 , 09:15 PM]
**What I did**: Added process priority to the scheduler.

**Details**:
Modified the Process class to assign a random priority (1-10) when a process object is created.

**Challenges**:
 Determining the best place to assign the priority without affecting the FIFO nature of the Round Robin ready queue.
**Solution**:
Modified the Process constructor to generate and assign the priority automatically using new Random().nextInt(10) + 1.
**Time spent**:
45 minutes
---

### Entry 3 - [October 8, 2026, 12:30 AM]
**What I did**:
 Implemented the context switch counter.
**Details**:
 Added a static counter to track how many times the CPU switches between threads during the simulation.
**Challenges**:
Finding the exact logical point in the scheduler loop where a context switch truly happens.
**Solution**:
Declared a static variable contextSwitches and incremented it inside the while loop right before executing or resuming a thread.
**Time spent**: 1 hour

---

### Entry 4 - [October 8, 2026, 01:45 AM]
**What I did**:
Calculated Waiting and Turnaround Times.

**Details**:
 Tracked arrival and finish times for each process to calculate the final metrics.
**Challenges**:
 Processes in Round Robin enter the queue multiple times, making it difficult to track their exact finish time
**Solution**:
Added logic to record finishTime only when remainingTime reaches zero, then calculated Turnaround Time (Finish - Arrival) and Waiting Time (Turnaround - Burst).
**Time spent**:
1 hour
---

### Entry 5 - [October 8, 2026, 03:00 AM]
**What I did**:
Created the final output table.
**Details**:
Formatted and printed the calculated metrics in a clean table at the end of the execution.
**Challenges**:
The final table printed duplicate rows for the same process because of the context switches adding them to the map multiple times.
**Solution**:
 Used new java.util.HashSet<>(processMap.values()) in the print loop to eliminate duplicate process objects and display a clean table.
**Time spent**:
 30 minutes
---

### Entry 6 - [October 10, 2026, 07:45 PM]
**What I did**:
Completed technical documentation Reflection and Technical Answers and Recorded the explanation video and uploaded it to Google Drive.
**Details**:
: Answered the reflection and technical questions in MY_WORK.md based on my code implementation
**Challenges**:
Tracing the exact output for Question 2 to show how a process is re-queued.
**Solution**:
Ran the code, copied the specific output snippet, and explained the context switch accurately
**Time spent**:
1.5 hour
---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [5 hours]

**Most challenging part**:
Tracking the accurate wait times and resolving the duplicate outputs in the final metrics table.
**Most interesting learning**:
Seeing how Thread.start() and Thread.sleep() can actually simulate the behavior of a real Operating System's CPU context switching.
**What I would do differently next time**:
I would test the data structures earlier to avoid the redundancy issue that required adding the HashSet later.
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

[I learned how Java executes multiple processes concurrently rather than sequentially,Using the Runnable interface allows a class to define its execution task and Calling Thread.start() begins the actual lifecycle of the thread. I also saw how Thread.sleep() is used to simulate CPU burst times. Finally using Thread.join() helped me understand how the main program waits before context switching.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[Calculating the waiting and turnaround times accurately was the hardest part. In a Round Robin scheduler single process executes multiple times before completion so This made tracking the exact finishTime very complicated. Additionally this repeated queuing caused my final table to display duplicate rows for the same process. It took effort to trace the execution flow and fix these issues.
Question 3: How did you overcome the challenges you faced?]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I fixed the timing issue by isolating the exact moment a process finishes. I added an if condition to check if remainingTime == 0 before recording the final end time. To fix the duplicate rows and I changed how the data is printed. I wrapped my map values in a HashSet. This naturally filtered out the repetitions and provided a clean output table.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is essential for building responsive applications that handle multiple tasks at once. For example, a web browser uses one thread to load HTML and another to fetch images. A media player can stream audio in the background while updating the user interface. Web servers also rely on it to serve thousands of client requests concurrently. This ensures that software remains highly interactive and efficient.]

### Optional: What would you like to learn more about?

[I want to learn more about thread synchronization and how to prevent race conditions when multiple threads modify shared variables]

### Optional: How confident do you feel about multithreading concepts now?

[Intermediate. I understand the thread lifecycle and scheduling, but I need more practice with complex synchronization]

### Optional: Feedback on the assignment

[It was a practical assignment. Implementing the logic myself made the theoretical concept of the Round Robin scheduler much clearer]

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

[A process has its own isolated memory, while a thread is a lightweight unit that shares memory within a process. We used threads here because they have lower creation overhead and allow faster context switching than real OS processes. In our code the Process class merely simulates a process, but it actually executes using a real Java thread when we call new Thread(process).]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[If a process does not finish within its time quantum, it is paused and moved back to the end of the ready queue. This constant re-queueing is essential for fairness because it prevents long processes from monopolizing the CPU.]

Example from my output:

[⏸ P4 completed quantum 5000ms | Overall progress: [████████  ] 83% Remaining time: 2043ms ↻ P4 yields CPU for context switch ➕ P4 added to ready queue | Burst time: 12043ms Priority: 4 ┌ Ready Queue └ [P6 -> P9 -> P10 -> P11 -> P12 -> P4]]
```

**Explanation of example:**
[In the output snippet above, process P4 completed its allowed time quantum but still had 2043ms of remaining time. It yielded the CPU for a context switch and was"added to ready queue" (re-queued) at the end of the list. It had to wait for its next turn, which perfectly demonstrates how the Round-Robin algorithm shares CPU time fairly.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state?]
P1 enters the New state when it is instantiated as a thread using new Thread(process) inside the addProcessToQueue() method, before execution starts.
2. **Runnable**: [When does P1 become Runnable?]
P1 becomes Runnable the moment currentThread.start() is called in the main scheduler loop, waiting for the OS to allocate CPU time.
3. **Running**: [When is P1 Running?]
 P1 is in the Running state when the CPU actually executes the instructions inside its run() method.
4. **Waiting**: [When and why would a thread be Waiting?]
The main thread waits when currentThread.join(timeQuantum) is called, while P1 itself enters a timed waiting state using Thread.sleep() to simulate CPU execution.
5. **Terminated**: [When is P1 Terminated?]
P1 enters the Terminated state when its remainingTime reaches zero and the run() method completes its execution.
## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [OS CPU Time-Sharing Schedule]

**Description**:
[ Modern operating systems like Windows or Linux manage multiple running applications (for example a browser and a music player) simultaneously on a single processor. The OS assigns each application a small time quantum to execute before performing a context switch to the next application.]

**Why Round-Robin works well here**:
[Round-Robin guarantees fairness and high responsiveness. By rapidly cycling through the applications, it creates the illusion that all programs are running at the exact same time without allowing one heavy process to freeze the entire system.]

### Example 2: [Web Server Request Handling]

**Description**:
[A web server such as Apache receives thousands of concurrent HTTP requests from different clients trying to load a website. The server places incoming client requests into a queue and allocates a small time quantum to process a portion of each request before moving to the next.]

**Why Round-Robin works well here**:
[ This approach ensures predictability and fairness for all users. If one user requests a massive file download, the Round-Robin mechanism prevents that single large task from monopolizing the server, ensuring that users requesting small files still receive fast responses.]

## Summary

**Key concepts I understood through these questions:**
1.How to use Thread.start() and Thread.sleep() to simulate CPU execution and delays.
2.The mechanical flow of a Round-Robin scheduler, including queue management and preempting processes.
3.How to track exact timing metrics (turnaround and wait times) even when processes are interrupted and re-queued.

**Concepts I need to study more:**
1.Advanced thread synchronization using locks and semaphores to prevent race conditions.
2.How the Java Virtual Machine (JVM) maps Java threads directly to native OS threads.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ✅] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [✅ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [✅ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ✅] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ✅] Code compiles and runs with no errors
- [ ✅] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [✅ ] Each feature has clear comments

**Commits**
- [ ✅] **At least 3 meaningful commits, ideally 6 or more**
- [ ✅] **One commit per feature**
- [ ✅] Commits are spread over **different dates** (not all in the last hour)
- [✅ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [✅ ] Full name and student ID filled in at the top
- [ ✅] Development log has **5+ entries** on different dates
- [ ✅] Reflection: 4 questions, 5-7 sentences each
- [ ✅] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ✅] No `[...]` placeholders left
- [ ✅] No section headers deleted

**Video**
- [ ✅] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ✅] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [✅ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ✅] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.