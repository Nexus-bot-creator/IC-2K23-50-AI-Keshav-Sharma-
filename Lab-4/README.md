# Lab-4: Knowledge Representation in Python

This folder contains four Python programs demonstrating different approaches to representing, organizing, and retrieving knowledge.

## Programs

### 1. `Frame_Representation.py` — Frame Representation

Demonstrates how knowledge can be organized into **frames**, where each frame represents an entity and stores its properties as slots.

The program defines three frames:
- **Student** — name, age, course, department, and university.
- **Teacher** — name, age, subject, department, and university.
- **Course** — name, duration, degree, and department.

**Features:**
- Display all defined frames.
- Search for and display a specific frame by name.
- Handle frame names that are not found.

### 2. `Medical_Knowledge_Representation.py` — Rule-Based Medical Knowledge System

Demonstrates a simple rule-based expert system that compares user-entered symptoms with predefined symptom sets.

The program includes rules for:
- Common Cold
- Flu
- Malaria
- Migraine
- Food Poisoning

**Features:**
- Accept symptoms separated by commas.
- Match the entered symptoms against the predefined rules.
- Display possible conditions and the number of matched symptoms.
- Sort matching conditions by the number of symptoms matched.

> **Disclaimer:** This is an educational demonstration, not a medical diagnosis. Consult a qualified healthcare professional for medical advice.

### 3. `Semantic_Network_Construction.py` — Semantic Network Construction

Demonstrates a semantic network using nodes and relationships to represent connected concepts.

The network includes:
- **Student** — is a Person, studies a Course, and belongs to a University.
- **Teacher** — is a Person, teaches a Course, and works at a University.
- **Course** — is offered by a University and has a Subject.
- **University** — has a Department.

**Features:**
- Display the complete semantic network.
- Search for a node and display its relationships.
- Handle node names that are not found.

### 4. `University_Knowledge_Base.py` — University Knowledge Base

Demonstrates a simple knowledge base containing university student, teacher, and course information.

The sample data includes:
- Student records identified by student IDs.
- Teacher records identified by teacher IDs.
- Course codes and their full names.

**Features:**
- Search for a student using a student ID.
- Display teacher information and their subjects.
- Display available courses and their full names.
- Handle student IDs that are not found.

## Requirements

- Python 3.x
- No external Python packages are required by these programs.

## How to Run

Open a terminal in this folder and run any program using Python:

```bash
python3 Frame_Representation.py
python3 Medical_Knowledge_Representation.py
python3 Semantic_Network_Construction.py
python3 University_Knowledge_Base.py
```

Each program runs independently. Follow the on-screen menu or prompts to interact with it.

## Concepts Demonstrated

| Program | Main concept |
|---|---|
| `Frame_Representation.py` | Frames, slots, and attribute-value representation |
| `Medical_Knowledge_Representation.py` | Rule-based knowledge and symptom matching |
| `Semantic_Network_Construction.py` | Nodes, relationships, and semantic links |
| `University_Knowledge_Base.py` | Structured facts and information retrieval |

---

**Note:** The records and rules in these programs are sample educational data.
