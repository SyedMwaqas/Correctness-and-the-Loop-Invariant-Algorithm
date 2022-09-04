# Correctness and the Loop Invariant Algorithm
In computer science, you could prove it formally with a loop invariant, where you state that a desired property is maintained in your loop. Such a proof is broken down into the following parts:

    Initialization: It is true (in a limited sense) before the loop runs.
    Maintenance: If it's true before an iteration of a loop, it remains true before the next iteration.
    Termination: It will terminate in a useful way once it is finished.
