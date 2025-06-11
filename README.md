# Chat-App UML Diagrams

This repository contains the PlantUML source files for the Medium article:

> **Stop Shipping Blind: The 3-Diagram Workflow Every Feature Needs**  
> Use-case → ERD → Class = fewer bugs, happier stakeholders

---

## Contents

- `usecase.puml`  
  The use-case diagram showing actors and their interactions.

- `erd.puml`  
  The ERD (entity-relationship diagram) with primary keys, foreign keys, cardinalities, and the composite key on `Membership`.

- `class-overview.puml`  
  The system-level class diagram mapping entities to application and infrastructure classes.

- `upload-strategy.puml`  
  The feature-level class diagram (Strategy pattern) for the upload pipeline.

---

## Rendering Diagrams Locally

1. **Install PlantUML** and Graphviz  
   ```bash
   # macOS (Homebrew)
   brew install plantuml graphviz

