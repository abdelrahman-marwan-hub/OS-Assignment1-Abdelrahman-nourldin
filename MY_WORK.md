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
| **Full Name** | abdelrahman marwan moustafa noureldin |
| **Student ID** | 446052720 |
| **University Email** | 446052720@std.psau.edu.sa |
| **GitHub Username** | abdelrahman-marwan-hub |
| **Repository Link** | https://github.com/abdelrahman-marwan-hub/OS-Assignment1-Abdelrahman-nourldin.git |
 
---

## 🎥 Video Link

**Video Link**: https://youtu.be/oNo7HQcGF3I?si=VVK4LxIuRRlw0DkB

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

### Entry 1 - [October 13, 2026, 5:00 AM]
**What I did**: set up GitHub, read the assignment, and set my student ID

**Details**:
created my GitHub account with my university email.
forked the starter repository and renamed it.
read the README.md and the assignment PDF.
made a simple plan for the three features.
changed the student ID in the code to 446052720
committed and pushed: Set my student ID: 446052720

**Challenges**: There were many instructions, so it was hard to know where to start

**Solution**: I wrote a short list of the tasks and did them in order
**Time spent**: 2 hours 

---

### Entry 2 - [October 13, 2026, 7:00 AM ]
**What I did**: Added Feature 1 (priority) and Feature 2 (context switch counter)

**Details**: feature 1: added a priority field and a getPriority() method to the Process class
feature 1: made a random priority from 1 to 10 with 1 + random.nextInt(10)
feature 1: showed the priority in addProcessToQueue() and in the ready queue print

feature 2: added static int contextSwitchCount in SchedulerSimulation
feature 2: added contextSwitchCount++ before currentThread.start()
feature 2: printed "total context switches" at the end
made one commit for each feature

**Challenges**:my first counter gave 19 and not 20, because i only counted when the process changed

**Solution**:: i read the README.md again. it says to count each time a process starts running, so i count every Thread.start() now

**Time spent**: 3 hours

---

### Entry 3 - [october 13, 2026, 1:00 pm]
**What I did**: added feature 3 (waiting time tracking and summary table)

**Details**: added readyQueueEntryTime and totalWaitingTime to the Process class
wrote markReady(), recordWaitingTime(), getWaitingTime() and getTurnaroundTime()
called markReady() in addProcessToQueue()
called recordWaitingTime() right after processQueue.poll()

added a list called allProcesses to keep every process
printed a table with burst time, waiting time and turnaround time using printf
checked that turnaround time is equal to waiting time plus burst time

**Challenges**:this was the hardest part for me. i did not know when a process starts and stops waiting. at first i put the calculation inside run(), and the numbers were not correct

**Solution**: i moved it to the scheduler loop, after poll(), because that is when the process leaves the queue. a process can wait many times, so i add each wait to the total

**Time spent**: 4 hours

---

### Entry 4 - [october 14, 2026, 4:00 pm]
**What I did**: completed part a, part b and part c in MY_WORK.md

**Details**:
wrote the development log
answered the 4 reflection questions
answered the 4 technical questions
used my own program output (p4 was re-queued 2 times) for the ready queue question
checked my answers against my final code
committed and pushed the file to github

**Challenges**: it was hard to explain the thread states in simple english

**Solution**: i followed p1 in the code step by step: new Thread(), start(), sleep(), join()

**Time spent**: 4 and half hours 

---

### Entry 5 - [october 14, 2026, 9:00 pm]
**What I did**: record the demo video and submit the assignment

**Details**: 
recorded a 2 to 3 minute video with my screen and voice
showed my name, student ID, repository, the three features, the run in VS code, and the commit history
explained Thread.join() in my own words
uploaded the video and put the public link in MY_WORK.md
submitted the repository link on blackboard

**Challenges**:  i was nervous while recording the video, and it was hard to explain all the features within the time limit.

**Solution**:i prepared a short outline before recording and practiced explaining the main features. this helped me speak more clearly and finish the video on time.

**Time spent**: 1 and half hour 

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

**Total time spent on assignment**: [15 hours]

**Most challenging part**: the waiting time tracking 

**Most interesting learning**: Thread.join() makes the main thread wait, so only one process runs at a time

**What I would do differently next time**: Start earlier, commit more often, and write the log after each work session

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

i learned how to run code in a separate thread using the Runnable interface. when i call Thread.start(), the run() method of the process starts in a new thread. Thread.join() makes the main thread wait until the process finishes its quantum. Thread.sleep() is used to pretend that the process is using the cpu. i was surprised that a thread cannot start twice, so i create a new Thread each time a process goes back to the queue.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

the hardest part was feature 3, the waiting time. i had to decide when a process starts waiting and when it stops waiting. at first i put the calculation inside run(), but the right place is after processQueue.poll(). a process can wait many times, so i add each wait to totalWaitingTime . also, my context switch count was 19 at first, and i fixed it to 20.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

i tested after every small change by running the program in vs code. i read the readme again and followed it exactly, so the counter now counts every Thread.start(). to check feature3, i maنe sure that turnaround time is equal to waiting time plus burst time. i also saw that p3 has the smallest waiting time, so the result made sense. i made a separate commit for each feature, so it was easy to find problems.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

a web browser uses threads for tabs and downloads, so one slow page does not freeze everything. a music player plays a song in one thread and loads the next song in another thread. in a game, one thread draws the screen and another thread handles the player's input. an operating system works like my simulation: each program gets a small time quantum, and then the cpu switches to the next one.

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

a process is a running program with its own memory, and a thread is a smaller part inside a process that shares its memory. first, my threads share processQueue  and contextSwitchCount, but separate processes would not share memory. second, creating a thread with new Thread(process) in addProcessToQueue() is faster and lighter than creating a new process. 

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

when a process does not finish in its time quantum, it goes to the end of the ready queue. in my output, p4 has a burst time of 4288ms and the quantum is 2000ms, so it was re-queued 2 times and finished in its third turn. this is fair because no process keeps the cpu for a long time..

Example from my output:
```
⏸ P4 completed quantum 2000ms
  Remaining time: 2288ms
↻ P4 yields CPU for context switch

➕ P4 added to ready queue
...
(same again with 288ms remaining)
...
▶️ P4 executing quantum [288ms]
✓ P4 finished execution!

```

**Explanation of example:**

P4 used its full 2000ms but still had time left, so it yielded the CPU and was added to the queue again. This happened two times, and in the third turn P4 ran only 288ms and finished.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 is New when new Thread(process) is created in addProcessToQueue()

2. **Runnable**: P1 becomes Runnable when the main thread calls currentThread.start().

3. **Running**: P1 is Running when its run() method is executing.

4. **Waiting**: P1 enters the TIMED_WAITING state when it calls Thread.sleep(), while the main thread waits for P1 to finish when it calls currentThread.join().


5. **Terminated**: the thread finishes when its run() method ends.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling]

**Description**:
the os runs many programs, but the cpu has only a few cores, so it gives each program a small time slice and then switches. in my simulation, the process is the program, the time quantum is the time slice, and the context switch is the change to the next program.

**Why Round-Robin works well here**:
it is fair because every program gets the same time slice. it is responsive because no program waits too long, so the computer does not look frozen.

### Example 2: [web server handling many requests]

**Description**:
a web server gets many requests from many users at the same time. each request gets a short turn on a thread, like a process in my simulation.

**Why Round-Robin works well here**:
short requests do not wait for a long request, so users get fast answers. it is also fair because every request gets a turn.

## Summary

**Key concepts I understood through these questions:**
1.ohw Thread.start(), Thread.join() and Thread.sleep() work together.
2.how Round-Robin works with a time quantum and the ready queue.
3. how to calculate context switches, waiting time and turnaround time.

**Concepts I need to study more:**
1.thread synchronization (locks).
2.other scheduling algorithms, like priority scheduling.

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
