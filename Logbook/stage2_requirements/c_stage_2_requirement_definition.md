[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition

# Personas

## Persona: Gertrudes Germânica
### Summary 
| Attribute        | Details                                        |
| ---------------- | -----------------------------------------------|
| **Photo**        | ![Persona Name\|100](personas/gertrudes_germanica.jpeg)   |
| **Name**         | Gertrudes Germânica                            |
| **Age**          | 21 years old                                   |
| **Occupation**   | Student                                        |
| **Location**     | Oxford - England                            |
| **Goals**        | Balance passion with schoolwork effectively    |
| **Pain Points**  | Mastering time management                      |
| **Motivation**   | Wants to aprimorate her workflow and broaden her knowlegdge of Applied Medicine and Modern Arts |
| **Full Profile** | [📄 Read More](personas/gertrudes_germanica.md)  |

---
## Persona: Luís Leiteiro
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Persona Name\|100](personas/luis_leiteiro.jpeg)       |
| **Name**         | Luís Manuel Leiteiro                          |
| **Age**          | 18 years old                                  |
| **Occupation**   | Student                                       |
| **Location**     | Évora - Portugal                              |
| **Goals**        | Become a more organized person                |
| **Pain Points**  | Have an efficient way to study                |
| **Motivation**   | Wants to become a more organized person and use the AI agent to help him study |
| **Full Profile** | [📄 Read More](personas/luis_leiteiro.md) |

---





# Scenarios


## Scenario 1: Gertrudes sets up her page

On an afternoon she decided to find a new way to organise her studies so she search for a new organasition tool and found this product being advertised online and got interested so she **created and account**.  
On the main page she was asked to **create a subject** so she could start working. She chose the **subject name** and personalised it to her liking. After that she started **creating folders** and **uploading files** on her subject, choosing which ones would be **visible to the AI** and selecting if they are **contents or exercises**.  
When she is happy with the subject state, she can stop editing. After that, she can access the uploaded files at any time and also upload some more. She can also **download a zip file** with all the files.  
After uploading files, she **adds deadlines** and **study sessions**, specifying how often does she want to have them, on the subject, then she sees **everything displayed on her calendar**.  
---

## Scenario 2: Luís uses the AI features to help him study
Luís logs in to the app and goes straight to C-II selects the option to **upload a file**, choosing where to store it and selects the option to have **it visible to the AI** and that it is **content**, not worrying about where he puts it. He asks C-II AI to **do a summary** of the contents of that file.  
After he is done studying the summary and asking **questions to the AI** to understand it better, he goes back and selects the option to have the AI **make a quiz** for him. He uploads questions his professor provided him and selects it to be exercises. He **selects a quiz of 5 questions** and uses the files he wants as the info for the AI to use, then he waits a bit and uses that material to do exercises and study. After all that, he **saves that quiz** so he can review it at a later time.
---

# Requirements

-The application should allow users to create an account and login using their credentials like email and password;  
-The system should not be required to be installed on every machine;  
-The application should be intuitive;  
-The application should be able to handle multiple users without performance issues, thus being available at all times;  
-The user should be able to create a new subject and create new folders and upload files on it;  
-The subject should be able to be customised;  
-The user should be able to select if a file is “content” or “exercises” and if the AI agent should have access to it;  
-Subject content should be able to be viewed by the user;  
-The user should be able to add new files and change current files after the subject is created;  
-The user should be able to download all the files of a subject;  
-The user should be able to add deadlines and study sessions and choose how often they want to do study sessions (daily, weekly, during the weekend or week, etc.);  
-The system should be able to find interferences between study sessions;  
-The user should be able to see their calendar with every deadline and study session;  
-The user should be able to access the deadline/study session directly from the calendar;  
-The AI agent should be able to summarise the contents of a subject to the user;  
-The AI agent should be able to respond questions of the user with accuracy to the subject contents;  
-The AI agent should be able to create quizes for a user;  
-The quiz should have an interactive interface to promote a more engaging learning;  
-The user should be able to choose the number of questions and content of a quiz;  
-The user should be able to save the quiz and answer it later;  
-The AI agent should have a low response time.  

## C.1. Functional requirements
-The application should allow users to create an account and login using their credentials like email and password;  
-The system should not be required to be installed on every machine;  
-The user should be able to create a new subject and create new folders and upload files on it;  
-The subject should be able to be customised;  
-The user should be able to select if a file is “content” or “exercises” and if the AI agent should have access to it;  
-Subject content should be able to be viewed by the user;  
-The user should be able to add new files and change current files after the subject is created;  
-The user should be able to download all the files of a subject;  
-The user should be able to add deadlines and study sessions and choose how often they want to do study sessions (daily, weekly, during the weekend or week, etc.);  
-The system should be able to find interferences between study sessions;  
-The user should be able to see their calendar with every deadline and study session;  
-The user should be able to access the deadline/study session directly from the calendar;  
-The AI agent should be able to summarise the contents of a subject to the user;  
-The AI agent should be able to respond questions of the user with accuracy to the subject contents;  
-The AI agent should be able to create quizes for a user;  
-The user should be able to choose the number of questions and content of a quiz;   
-The user should be able to save the quiz and answer it later;  

## C.2. Non-functional requirements
-The application should be intuitive;  
-The application should be able to handle multiple users without performance issues, thus being available at all times;  
-The quiz should have an interactive interface to promote a more engaging learning;  
-The AI agent should have a low response time;  

---
[Back to main Logbook Page](hci_logbook.md)