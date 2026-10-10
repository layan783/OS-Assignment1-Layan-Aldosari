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
| **Full Name** | [Layan Nasser Aldosari] |
| **Student ID** | [446360212] |
| **University Email** | 446360212@std.psau.edu.sa |
| **GitHub Username** | [layan783] |
| **Repository Link** | [https://github.com/layan783/OS-Assignment1-Layan-Aldosari] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/1EmhFHy0PltjCKLQCI_lpuyqN7n4Ogww0/view?usp=drive_link]

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

### Entry 1 - [October 6, 2026, 9:00 PM]
**What I did**:Read the assignment instructions and reviewed the project requirements.

**Details**: 
- Read the assignment instructions to understand the required tasks.

- Reviewed the Round-Robin scheduling concept.

- Checked the three required features and the documentation requirements.

- Planned how to start working on the Java project.

**Challenges**: At first, I found it difficult to understand all the requirements and how the features were related to the original scheduler.

**Solution**:I read the instructions carefully and divided the assignment into smaller tasks.

**Time spent**: 2 hours

---

### Entry 2 - [October 7, 2026, 9:00 PM]
**What I did**: Updated my student ID and prepared the Java project.

**Details**:
- Opened the assignment repository on GitHub.

- Updated my student ID to 446360212 in SchedulerSimulation.java.

- Saved the change with the commit Update student ID for random number generation.

- Reviewed the code to understand how the scheduler works


**Challenges**: At first, I needed to understand where to make changes without affecting the original code.

**Solution**:I reviewed the Java file and made the required changes carefully

**Time spent**: 2 hours

---

### Entry 3 - [October 8, 2026, 4:00 PM]
**What I did**: Added Feature 1 to display random process priorities

**Details**:
- Added a random priority value for each process.

- Updated the output to display the priority next to the burst time.

- Ran the program to check the new output.

- Saved the changes with the commit Feature 1: Add random process priority display
  
**Challenges**:  I needed to display the priority values without changing the original scheduling behavior
  
**Solution**: I updated the process information and checked the output to make sure the program still worked


**Time spent**: 3 hours

---

### Entry 4 - [October 8, 2026, 8:30 PM]
**What I did**: Added Feature 2 to count CPU dispatches

**Details**:
- Added a counter to track how many times the CPU selected a process.

- Updated the scheduler to increase the counter during execution.

- Displayed the total count at the end of the program.

- Saved the changes with the commit Feature 2: Track CPU dispatch count.

**Challenges**: I needed to understand where the counter should be updated in the scheduler

**Solution**:I added the counter to the scheduling logic and ran the program to check the result

**Time spent**: 1 hour 

---

### Entry 5 - [October 8, 2026, 10:00 PM]
**What I did**: Added Feature 3 to calculate waiting time and turnaround time

**Details**:
- Added calculations for each process's waiting time and turnaround time.

- Updated the final output to display the process statistics.

- Ran the program to check that all processes completed successfully.

- Saved the changes with the commit Feature 3: Track process waiting and turnaround times

**Challenges**: I needed to understand how to calculate the process times and display them correctly

**Solution**:I updated the calculations and checked the final output after running the program

**Time spent**: 1 hour and 30 minutes

---

### Entry 6 - [October 9, 2026, 12:30 AM]
**What I did**: Worked on the assignment documentation.

**Details**:
- Opened and edited the MY_WORK.md file.

- Answered the reflection and technical questions.

- Used my program output to explain the ready queue behavior and thread lifecycle.

- Saved my work using the commit Update assignment documentation.

**Challenges**: I had difficulty understanding how to save my changes correctly in GitHub

**Solution**: I followed the editing steps and used Commit changes to save the documentation.

**Time spent**: 3 hours

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [12 hours and 30 minutes]

**Most challenging part**: Adding the three new features without affecting the original Round-Robin scheduling logic. Calculating waiting time and turnaround time was especially challenging

**Most interesting learning**:  I learned how Round-Robin scheduling manages processes using a time quantum and how to track CPU dispatches, waiting time, and turnaround time

**What I would do differently next time**:  I would plan my work earlier, test each feature separately, and update my Development Log after every work session

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

[I discovered that multithreading enables a program to use threads to handle several jobs. This project taught me how to specify a thread's job using the Runnable interface. I realized that Thread.start() initiates a thread's execution. Additionally, I discovered that Thread.join() causes the calling thread to wait for the completion of another thread. Each process in our program's execution duration is simulated with the aid of Thread.sleep(). The most fascinating thing I discovered was how Round-Robin scheduling distributes CPU usage among tasks.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[Implementing the waiting time feature was the most difficult aspect of this task. I initially had trouble understanding how to figure out how long each process waits in the ready queue. I had to comprehend the flow of processes between the CPU and the queue. Additionally, I had to ensure that the waiting time was accurately updated. I also needed to verify the final output table.Because I wanted the outcomes to meet the requirements of the assignment, this section needed more focus.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[By completing the task step by step, I was able to overcome the obstacles. I went over the instructions to make sure I understood what was needed for each feature. Before adding new variables or methods, I reviewed the current code. I ran the software to view the output and look for faults after making the necessary adjustments. I changed the output format and retested it after seeing that Burst Time was missing from the final table. Additionally, I discovered how to make changes to a Git commit and upload the updated version to GitHub.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Many programs that require to manage multiple tasks can benefit from multithreading. A web browser, for instance, can employ threads to load content while maintaining a dynamic user interface. A music app lets the user browse songs and play music. In order to distribute CPU time among various tasks, operating systems also employ scheduling mechanisms. Round-Robin scheduling was used in our assignment to show how processes might share the CPU. This made it easier for me to see how scheduling and multithreading ideas may enhance the responsiveness of actual programs.]

### Optional: What would you like to learn more about?
I want to know more about how operating systems handle several threads at once. Additionally, I'm curious about how various CPU scheduling strategies impact program performance. I believe that becoming more knowledgeable about these subjects will enable me to comprehend how actual apps operate.


### Optional: How confident do you feel about multithreading concepts now?
in the middle. I now understand how Round-Robin scheduling controls processes and how threads operate. Additionally, I learned how to compute turnaround and waiting times. I still need to practice writing multithreading code on my own, though.


### Optional: Feedback on the assignment
Although difficult, this assignment was beneficial. Instead of just learning the theory, it helped me grasp multithreading topics through real-world code. My understanding of the program improved once I added the three features and tested the results. The assignment, in my opinion, was a useful approach to practice GitHub and Java programming.


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

[A thread is a smaller unit of execution that shares memory with other threads in the same process, whereas a process is an independent program that often has its own memory space. In general, threads can be created and communicated with more quickly than individual processes. Instead of representing an actual operating system process, the Process class in our assignment represents a simulated process. For every simulated process, the addProcessToQueue() method creates a Java thread using new Thread(process). The scheduler may mimic several processes in a single Java program by using threads.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, a process that does not finish within its time quantum is placed at the end of the ready queue. In my simulation, the time quantum was 5000 ms and P2 had a burst time of 10971 ms. After its first 5000 ms, P2 still had 5971 ms remaining, so it returned to the ready queue. P2 was re-queued two times before finishing during its third CPU turn. This makes scheduling fair because other processes get a chance to use the CPU instead of waiting for P2 to finish.]

Example from my output:
```
[P2 executing quantum [5000ms]
Quantum progress: [███████████████] 100%
P2 completed quantum 5000ms │ Overall progress: [█████████░░░░░░░░░░░] 45%
Remaining time: 5971ms
P2 yields CPU for context switch

P2 added to ready queue │ Burst time: 10971ms │ Priority: 4
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P4 ? P5 ? P6 ? P7 ? P8 ? P9 ? P10 ? P11 ? P12 ? P13 ? P14 ? P15 ? P2]
└───────────────────────────────────────────────────────────────────────────────]
```

**Explanation of example:**
[In my output, P2 had a burst time of 10971 ms, while the time quantum was 5000 ms After the first turn P2 still had 5971 ms remaining, so it was added to the ready queue again. P2 was re-queued two times before it finished on its third turn. This gives other processes a chance to use the CPU and makes Round-Robin scheduling fair]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 starts in the New state when its thread is created using new Thread(process)]

2. **Runnable**: [P1 becomes Runnable when Thread.start() is called and it is ready to run]

3. **Running**: [P1 starts executing, and my output shows that it runs for 2730 ms]

4. **Waiting**: [During execution, Thread.sleep() puts P1's thread in the TIMED_WAITING state, while Thread.join() makes the main thread wait for P1 to finish.]

5. **Terminated**: [P1 finishes execution after 2730 ms, as shown in my output: P1 finished execution!]

P1 executing quantum [2730ms]
Quantum progress: [███████████████] 100%
P1 completed quantum 2730ms │ Overall progress: [████████████████████] 100%
Remaining time: 0ms
P1 finished execution!

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling for Multiple Programs]

**Description**:
[An operating system may run several programs that need to use the CPU. Each program gets a limited time quantum, and if it does not finish, it returns to the ready queue for another turn.]

**Why Round-Robin works well here**:
[Round-Robin gives each program a fair chance to use the CPU. Context switching allows the CPU to move between programs, which helps keep the system responsive.]

### Example 2: [Web Server Request Handling]

**Description**:
[A web server may receive requests from many users at the same time. A Round-Robin approach can give each request a turn to be processed instead of letting one request use all the processing time.]

**Why Round-Robin works well here**:
[Round-Robin helps distribute processing time fairly between requests. Context switching allows the server to move between tasks, which can improve responsiveness when many requests need attention.]

## Summary

**Key concepts I understood through these questions:**
1.The difference between a process and a thread
2.How Round-Robin scheduling uses a time quantum and a ready queue
3.How context switching allows different processes to share the CPU

**Concepts I need to study more:**
1.The different states of the thread lifecycle
2.How waiting time and turnaround time are calculated

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
