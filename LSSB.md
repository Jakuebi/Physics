# The Lahlou Simulation Synchronicity Bound (Conjecture)
(Pronounced LAH-LOO)

## Author
* **Name:** Jacob Lahlou
* **Date:** 28 May 2026
* **Status:** Informal Conceptual Conjecture

## Abstract
Assuming that time moves in discrete intervals (ticks), and that the universe is algorithmically irreducible, **no physical process can perfectly predict via simulation the future state of a simultaneously occurring physical system before the physical system takes on that future state.** This is irrelevant of the computational abilities of the simulating process, but instead rooted in the discreteness of time and algorithmic irreducibility of the universe that force the simulated system to run, at best, in perfect synchronicity with the physical system, but never before.

## Assumptions
* Time is not continuous but rather divided into finite discrete intervals (ticks).
* The physical behavior of the universe and all physical systems within it are algorithmically irreducible; there exists no mathematical shortcut or compressive function to perfectly describe physical behavior in less steps than are taken by the universe.
* A perfect simulation cannot guess, or make any intermediate steps of what is being simulated, S. For each sequential frame of the perfect simulation, (K, X), it must be found that there exists $S_{k - n - 1}$ = $T_{k - 1}$ and $S_{k - n}$ = $T_{k}$ OR $S_{k - n}$ = $T_{k}$ and $S_{k - n + 1}$ = $T_{k + 1}$, where $n {\geq} 0$ and $S_{k}$ corresponds to the state of S at respective time-interval k while $T_{k}$ corresponds to X of (K, X) from T when K = k.
*
*   at every respective time-interval K the state of what is being simulated must exactly match X. Additionally, a perfect prediction must be a state taken from a perfect simulation. 

## Core Argument
In an algorithmically irreducible universe the perfect simulating physical process, T, cannot mathematically shortcut the evolution of the physical system, S, into the future state, F. This forces T to compute F in the same number of steps S takes to evolve into F, restricting the prospect of T computing F prior to S’s evolution into F to the avenue of T computing steps faster than S can physically evolve through steps. This may sound plausible at first, but when considering that T is a physical system alike S, its computation is embedded in its physical evolution from its own current state to its own future state. Furthermore, with the addition of discrete time intervals, there is a bottleneck to how fast this embedded physical computation within T can take place, the same bottleneck which limits S’s evolution into F, thus T must compute the steps needed to simulate F in at least the same amount of time it takes S to evolve through the same steps. The skipping and/or guessing of steps from T is also prohibited as this would violate the requirement of a perfect prediction, as the simulation would no longer match the physical evolution of S at each respective time interval. Even when T is a perfect simulating process with as much energy, information, computational power and speed as it needs, it is still bound by this conclusion and at best can only match the evolution of S in real-time step by step, never outpacing it or arriving at F prior to it.
