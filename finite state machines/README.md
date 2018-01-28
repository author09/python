
### implements deterministic Finite automaton(or just FA) and non-deterministic finite automaton in python


## Finite Automaton

An FA is described by its states and its transitions: each transition for a state specifies an input and what state in the FA that input leads to. An FA can be illustrated as a graph with state labels in circles and edge labels for transitions.
![alt text](https://github.com/author09/python/blob/master/finite%20state%20machines/dfa_.png "dfa illustration")

### Objective
Read a file representing a finite automaton: indicating its states and input->state transitions. A file containing the lines mentioned below represents the FA drawn above.
even;0;even;1;odd
odd;0;odd;1;even
Here even is the state and 0-->even and 1-->odd are the transitions from the even state.
Store this file in a dictionary and then:
Read a file storing the start-state and inputs to process (each line in the file contains this combination); repeatedly processes these lines, computing the results of the finite automaton on each input, and then prints the results.
Sample input:
even;1;0;1;1;0;1
even;1;0;1;1;0;x  #deal with invalid input
odd;1;0;1;1;0;1

The result is:
Start state = even
  Input = 1; new state = odd
  Input = 0; new state = odd
  Input = 1; new state = even
  Input = 1; new state = odd
  Input = 0; new state = odd
  Input = 1; new state = even
Stop state = even

Use <b>dfa.ipynb</b> with <b>state_transition.txt</b> and <b>input.txt</b> as sample inputs

