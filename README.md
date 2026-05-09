# OS Project C3 - CPU Scheduling Simulator

## Project Description

This project is a web-based CPU Scheduling Simulator developed for an
Operating Systems course (C3).\
It demonstrates and compares two scheduling algorithms:

- Preemptive Priority Scheduling\
- Round Robin Scheduling

The system allows users to input processes with Arrival Time, Burst
Time, and Priority, then visualizes execution using a Gantt Chart and
calculates key performance metrics such as:

- Waiting Time (WT)
- Turnaround Time (TAT)
- Response Time (RT)
- Average WT and TAT

The goal is to help students understand CPU scheduling behavior through
an interactive interface.

## Requirements

- Any modern web browser (Chrome, Edge, Firefox, etc.)
- No installation or backend required

## How to Run

### Option 1

1.  Open `index.html`
2.  Run directly in browser

### Option 2 (VS Code)

1.  Open folder in VS Code
2.  Install Live Server extension
3.  Click "Open with Live Server"

### Option 3 (Use a Hosted Demo)

1.  Use this link: https://ffady299gamer.github.io/OS/

## Input Format

ArrivalTime,BurstTime,Priority\
Example: 0,5,2 2,3,1 4,1,3

Rules: - Priority: lower number = higher priority - BT must be \> 0 - AT
must be \>= 0

## Team Members

- Fady Ossama\
- Abanoub Bassem\
- Peter Nemr\
- Abdelrahmen Wael\
- Jan George\
- Andraws Albert

## Features

- Preemptive Priority Scheduling
- Round Robin Scheduling
- Gantt Chart visualization
- Input validation
- Average metrics calculation


