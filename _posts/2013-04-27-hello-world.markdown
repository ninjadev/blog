---
layout: post
title: Operating Systems
author: perper
ingress: Operating systems are part of our every day worlds, but do you know how they work on the inside? Read more to find out the 7 best things about operating systems, including one you never expected!
---

#Operating Systems

## Introduction

An operating system (OS) is a collection of software that provides an abstract machine on top of a physical machine. The OS provides resource management. An OS makes a computer easier to use for end users and programmers. Typical services provided by an OS includes storage/file systems, process/thread management, security and communications.

## Processes

A process is an instance of a computer program that is being executed. It contains the progam code and its current memory state. A CPU can execute a single process at a time. Multiprogramming is a way for CPUs to fake concurrency by switching between different processes, often quickly. The Scheduler, using a schelduling algorithm, decides which process gets to use a CPU at any given time.

### Scheduling

Scheduling algorithms should be fair and balanced. For batch systems, the goal is to maximize process throughput, minimize turnaround time, and maximize CPU utilization. For interactive systems, the goal is to minimize response time, and ensure proportionality in latency (meeting the user's expectations). For real time systems, the goal is to meet deadlines and behave predictably.

A scheduling algorithm can either be preemptive or non-preemptive. A non-preemptive lets active processes decide when they are done using the CPU, while a preemptive algorithm can decide to switch processes at any time.

#### Scheduling Algorithms in Batch Systems

First-Come First-ServedNon-preemptive. Active processes are run to completion or blockage. New or unblocked processes are put in the ready queue. Maximizes CPU usage.Shortest Job FirstNon-preemptive. Uses statistics to make educated guesses about run-time of processes. The ready queue is a priority queue prioritizing the shortest jobs first. Minimizes turnaround.Shortest Remaining Time NextPreemptive. Like Shortest Job First, except a new process may take the place of the active process if its remaining time is lower than that of the active process.

#### Scheduling Algorithms in Interactive Systems

||Round-Robin Scheduling||Preemptive. Each process is assigned a time interval, or quantum. Processes that run longer than quantum are switched. Switching also occurs when the actuve process becomes blocked, or terminates. The quantum time must be tweaked to allow the best balance of response time and CPU utilization.||
||Priority Scheduling||Preemptive. Processes are given a priority score, assigned statically or dynamically. The ready queue is a prority queue on process priority. May use quantums.||
||Shortest Process Next||Preemptive. Estimates which process is shortest, and prioritizes accordingly.||
||Guaranteed Scheduling||Preemptive. When there are n processes, each process gets 1/n CPU cycles.||
||Lottery Scheduling||Preemptive. Prioritize processes at (optionally weighted) random.||

#### Scheduling Algorithms in Real Time Systems

TBD.

