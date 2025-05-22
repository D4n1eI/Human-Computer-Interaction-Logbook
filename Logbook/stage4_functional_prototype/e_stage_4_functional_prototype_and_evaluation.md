[Back to main Logbook Page](../hci_logbook.md)

---

# E. Functional Prototype and Evaluation

# Prototype
## Introduction
        We decided to create an app using Electron, with HTML, CSS, and JavaScript because the Electron environment provides us with access to many Node.js modules that help us recreate the same workspace we had in our low-fidelity prototype.
        We also built a working installer for multiple operating systems by leveraging some of Electron’s additional features. This made development easier, especially since some team members use Windows while others use Linux.
## Tasks
        We implemented the same tasks from the low-fidelity prototype, but with a couple differences.
        We also removed the calendar related task and added a new subtask that allows users to upload a file, rather than just displaying it.
## Notes
        Given our workload and limited time for this project, and even though our app is designed to be “all-in-one”, we chose not to implement some features in this first iteration. These features are marked with a “Not implemented yet” modal, such as the calendar view, editing subjects, user profiles and more.
        For simplicity, all pages are hardcoded. As a result of this implementation tactic any tasks related to user input, such as entering text or selecting a color, must follow specific values. We created a 'prompts.md' file to guide testers on exactly what to type. When a task that requires specific inputs recognizes wrong information, it instead displays a message warning the user of that wrong input. Chats with open input don't display this message, but only respond to some specific messages as well. This is done so that it keeps the feeling of an AI chat page instead of just another "input-response" UI segment.
# E.X. User Evaluation

TODO

---
[Back to main Logbook Page](../hci_logbook.md)

---