# UML Validation & Consistency Checklist

This checklist verifies the correctness, consistency, and traceability of the UML models
used in this repository.

---

## 1. Syntax Check

- [x] Use-case diagram uses correct UML notation (Actor, Use Case, Association)
- [x] Class diagram uses correct UML notation (Class boxes, attributes, associations)
- [x] No syntax or structural errors found in the diagramming tool
- [x] Relationship arrows and lines are used correctly

---

## 2. Naming Consistency

- [x] Actor name **Student** is consistent across diagrams
- [x] Class names **Student** and **Course** match entities referenced in use cases
- [x] Use-case names follow *verb + object* format  
  (e.g., *Register Course*, *Check Prerequisite*)
- [x] No ambiguous or conflicting names are used

---

## 3. Associations & Multiplicities

- [x] Association between **Student** and **Course** is clearly defined
- [x] Multiplicities are shown on associations where applicable
- [x] Multiplicity values are logically correct for the domain
  (e.g., one student can register for multiple courses)

---

## 4. Traceability

- [x] Each use case maps to at least one class responsibility
- [x] *Register Course* use case is handled by **Student** and **Course** classes
- [x] *Check Prerequisite* use case is related to the **Course** class
- [x] All system behaviors shown in use cases are supported by the class diagram

---

## 5. Overall Validation Result

- [x] UML models are internally consistent
- [x] UML models are traceable to system requirements
- [x] UML models are ready for versioning and review in GitHub
