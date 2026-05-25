# Medical Expert System - Knowledge Representation

## Project Description
A rule‑based expert system that diagnoses possible illnesses from a set of symptoms. Built for the APT 3020B lab.

## Objectives
- Represent medical knowledge using facts and rules.
- Implement a forward‑chaining inference engine.
- Apply logical reasoning to identify diseases.
- Demonstrate proper Git/GitHub documentation.

## Symptoms Used
Fever, Headache, Cough, Chest Pain, Sneezing, Runny Nose, Fatigue, Sore Throat, Vomiting, Diarrhea

## Diseases Detected
Malaria, Pneumonia, Flu, Food Poisoning

## Rules Applied
| IF                                                                 | THEN          |
|--------------------------------------------------------------------|---------------|
| Fever AND Headache AND Fatigue                                     | Malaria       |
| Cough AND Chest Pain AND Fatigue                                   | Pneumonia     |
| Sneezing AND Runny Nose AND Sore Throat                            | Flu           |
| Vomiting AND Diarrhea AND Fatigue                                  | Food Poisoning|

## Technologies Used
- Python 3.x
- JSON for knowledge base
- Git & GitHub for version control

## How to Run the Program
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/APT3020-Knowledge-Representation-Lab.git
   cd APT3020-Knowledge-Representation-Lab


## Screenshots of the working system
<img width="914" height="151" alt="Screenshot 2026-05-25 212504" src="https://github.com/user-attachments/assets/cf8b456c-2e3e-4613-9f66-e4464251ca86" />
A text box appears so that the patient can answer if they have the symptoms.



<img width="543" height="98" alt="Screenshot 2026-05-25 212552" src="https://github.com/user-attachments/assets/e733c2f3-cc73-4eb6-8c8e-69a52c4c8ac1" />
The system then tells them what disease they may have.



<img width="574" height="137" alt="image" src="https://github.com/user-attachments/assets/698f8611-95d3-43c0-b40c-e5d3d267c61b" />
If a patient keys in a series of symptoms that the system does not have a definite disease, it displays the above message.


## Simple GUI for the system
It has two windows: one where the patient ticks their symptoms and another that displays the diagnosis


<img width="1125" height="567" alt="Screenshot 2026-05-25 213541" src="https://github.com/user-attachments/assets/13b26512-3923-4be7-937d-bb691a03c4b2" />



<img width="1039" height="566" alt="image" src="https://github.com/user-attachments/assets/827637c4-2855-4b8e-8665-f0ca62f89bb8" />

