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

Ex: GNFA
![image](https://github.com/user-attachments/assets/1589dbbd-344e-4e2d-a47f-da874cc5738c)

DFA to GNFA:

![image](https://github.com/user-attachments/assets/e54911c3-d509-4bc7-997b-9e74e6849ffa)
![image](https://github.com/user-attachments/assets/1e87d836-2f93-4fa9-b883-dd61943d57e4)

Converting a DFA to a regular expression

![image](https://github.com/user-attachments/assets/fef5ecd8-de1c-408f-b6c7-1d2567781b72)
![image](https://github.com/user-attachments/assets/ad86a73b-d0ca-4bb5-84a6-0b12a4925448)
![image](https://github.com/user-attachments/assets/2e5a7c90-a09b-4c30-a904-4f9452176ca8)
![image](https://github.com/user-attachments/assets/3545582a-0726-4a33-afe0-39a32090539d)
![image](https://github.com/user-attachments/assets/6bf613ba-ee15-45cf-8fda-e7c5a61112e9)


