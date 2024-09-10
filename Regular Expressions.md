Ex: (ab+a)*

![image](https://github.com/user-attachments/assets/0784d43c-072f-43b3-8a65-4adc3ffa5cc4)

Ex: (a+b)*aba

![image](https://github.com/user-attachments/assets/993aa0b5-b46d-41f8-8a03-944c98c3b702)

A Generalized Nondeterministic Finite Automaton (GNFA) is an NFA wherein the transition arrows may have any regular expression as labels (instead of only members of the alphabet or λ)
- The start state has transition arrows going to every other state, but no arrows coming in from any other state.
- There is only a single accept state, and it has:
    - arrows coming in from every other state
    - no arrows going to any other state
    - qaccept does not equal qstart
- Except for qstart and accept, for every state:
    - one arrow goes from it to every other state
    - on arrow goes from it to itself

Ex: ![image](https://github.com/user-attachments/assets/1589dbbd-344e-4e2d-a47f-da874cc5738c)

