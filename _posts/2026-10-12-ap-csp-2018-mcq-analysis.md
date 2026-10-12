---
layout: post
title: "AP CSP 2018 Practice Exam: MCQ Analysis"
description: "My practice exam results, College Board skill analysis, Big Idea strengths and weaknesses, and next steps."
permalink: /csp/2018-mcq-analysis/
categories: [CSP, Reflection]
toc: true
comments: true
---

## Exam result

I scored **43 out of 66 (65.2%)** on the 2018 AP Computer Science Principles practice multiple-choice exam. After going through the questions I missed, I noticed that I usually did better when I needed to recognize a concept or interpret data than when I had to trace an algorithm through several steps. I also lost points on questions that asked for two answers.

## 1. College Board Analytics: strengths and weaknesses

The strongest areas in my question-by-question results were:

| Skill | Correct | What went well |
|---|---:|---|
| 3.B | 4/4 | Understanding and calling procedures |
| 5.E | 4/4 | Copyright and responsible use of computing |
| 5.B | 6/7 | Working with data and what it can tell us |
| 4.B | 5/6 | Recognizing what algorithms and program steps accomplish |

My lowest-performing skills included **1.D (6/13)**, **5.A (1/3)**, **3.C (2/4)**, and **4.C (2/4)**. The questions I missed in these areas involved tracing code, interpreting Internet communication, generalizing procedures, and debugging algorithms.

A few mistakes explain the pattern:

- **Q14 and Q37 (loops):** I missed how the order of statements affects the output or the work a program performs. Both problems required looking closely at what happens inside a loop versus after it.
- **Q63 (counting primes):** I didn't recognize that setting the counter to zero *inside* the loop would reset it every iteration. There was also an extra increment that would make the count incorrect.
- **Q54 and Q60 (abstraction):** I need to review how reusable procedures and lists can replace repetitive code. A general `Power(n, m)` procedure, for example, covers more cases than separate procedures for squaring and cubing.
- **Q6 and Q15 (Internet):** I confused the purpose of the IETF and overlooked the role of IP addresses in Internet communication.
- **Q24 and Q59 (compression):** I mixed up lossless and lossy compression. Lossless encoding lets the original data be recovered, while lossy compression discards some information.
- **Q50 and Q52 (algorithms):** I confused linear and binary search and missed another valid order for steps in the palindrome algorithm.

## 2. Strengths and weaknesses by Big Idea

| Big Idea | Score | Accuracy |
|---|---:|---:|
| **1. Creative Development** | 3/5 | 60.0% |
| **2. Data** | 11/16 | 68.8% |
| **3. Algorithms and Programming** | 20/30 | 66.7% |
| **4. Computer Systems and Networks** | 2/4 | 50.0% |
| **5. Impact of Computing** | 7/11 | 63.6% |

### Strongest: Big Idea 2 — Data

Data was my highest-scoring Big Idea at **68.8%**. I handled most questions that asked me to interpret datasets, compare available information, and figure out what data could be used to answer. Still, I need to review compression and think more carefully about which information is lost or preserved.

### Another relative strength: Big Idea 3 — Algorithms and Programming

I scored **66.7%** in Algorithms and Programming and did especially well with procedure calls. The weaker parts were developing algorithms (**1/4** in topic 3.9) and developing procedures (**0/2** in topic 3.13). That tells me I can often identify what a procedure does, but I have more trouble when I need to check exactly how the steps work together.

### Weakest: Big Idea 4 — Computer Systems and Networks

My lowest score was **50%** in Computer Systems and Networks. This Big Idea only had four questions, so the percentage is based on a small sample, but both missed questions involved Internet communication. I need to revisit how devices use IP addresses and why organizations such as the IETF establish open standards and protocols.

### Big Ideas 1 and 5

I scored **60.0%** in Creative Development and **63.6%** in Impact of Computing. In these areas, I need to review how changes to a program affect its behavior and think more carefully about the limitations and consequences of computing. For example, I missed a question about crowdsourcing because I overlooked that some computational problems cannot be solved efficiently, even with more participants.

## 3. Connection to my Ground Zero assessment

In my [Ground Zero assessment](https://github.com/nathantrieu360/portfolio/issues/1), I ranked myself **2/5 in JavaScript/Coding Challenges**, **2/5 in Git/GitHub**, and **1/5 in Portfolio/GitHub Pages**. At that point I was still relying on other people to tell me what to enter in the terminal and how to save work to GitHub.

Since then, I've gotten more comfortable opening my portfolio in VS Code, making commits, and working through pull requests. The MCQ results show that becoming more comfortable with development tools doesn't automatically mean I understand every programming concept. I still need practice following what a program does line by line, especially when variables are updated inside loops.

I also ranked myself **3/5 in Learning Through Mistakes** at Ground Zero. Reviewing these questions gives me a more specific way to improve instead of just looking at the overall score.

## 4. What I'll work on next

1. **Trace loops on paper:** Write down variable values after every iteration before choosing an answer.
2. **Review algorithms and abstraction:** Practice comparing linear and binary search, recognizing reusable procedures, and using lists instead of repeated variables.
3. **Study the Internet and data topics:** Review IP addresses, the IETF, Internet protocols, and lossy versus lossless compression.
4. **Double-check select-two questions:** Evaluate each statement separately so I don't miss a second correct option or choose an extra incorrect one.
5. **Redo missed questions without looking at the key:** Explain why the correct answer works, not just what letter it is.

For the next MCQ, my goal is to improve on questions involving algorithms and procedures while keeping my stronger performance in data interpretation. I want to understand what caused each mistake so that I can avoid repeating it.
