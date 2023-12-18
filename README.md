# Lottery Scheduling Implementation
### Introduction
This project demonstrates the Lottery Scheduling algorithm, a randomized process scheduling algorithm used in operating systems. The Lottery Scheduling algorithm assigns tickets to processes, and a lottery is held to determine the next process to be executed based on the winning ticket.
## Characteristics
 * Lottery Tickets: Every process is allotted a specific number of tickets, symbolizing its portion of the CPU.
 * Randomized Scheduling: The CPU scheduler picks a ticket at random, and the process holding that ticket is scheduled next.
 * Adaptability: Simple to assign and reallocate tickets according to process needs or system policies.
 * Fairness in Lottery Scheduling: Ensures an equitable distribution of opportunities (lottery tickets) among processes, preventing resource dominance and guaranteeing fair access to CPU time and system resources
   Gantt Chart:
| Round 1: P3 | Round 2: P2 | Round 3: P1 | Round 4: P2 | Round 5: P4 | Round 6: P5 | Round 7: P3 | Round 8: P5 | Round 9: P3 | Round 10: P1 |

