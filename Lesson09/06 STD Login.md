### Login
Draw a State Transition Diagram for an application login:

- A correct attempt logs the user in
- 3 failed attempts block the account

#### Solution

<img width="659" height="457" alt="image" src="https://github.com/user-attachments/assets/28c5d375-ee85-44b8-85ae-2f0002df18e1" />

Alternative implementations:

- Showing an "account blocked" state
- Creating one transition for "1st pwd wrong" and another one for "2nd pwd wrong" (could be unmanageable if the number of attempts is big)
