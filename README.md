
---

# Box & Lid Assembly: Parametric Design in Fusion 360

A precision-engineered enclosure project demonstrating **top-down design** methodologies, component-level activation, and hardware integration using the McMaster-Carr library. This project focuses on creating a functional, manufacturable assembly with integrated fasteners.

## 🛠 Features & Workflow

### 1. Component-Based Architecture
The project follows a strict "Rule #1" workflow in Fusion 360:
*   **Component Activation:** Every part (Box, Lid) was created as a discrete component to maintain a clean timeline and ensure local coordinate systems remain organized.
*   **In-Context Design:** The lid and fastening points were modeled directly referencing the box geometry, ensuring a perfect flush fit without manual measurement entry.

### 2. Modeling Techniques
*   **Offset Sketching:** Used to create precise clearances between the lid and the inner walls of the box.
*   **Tapped Holes & Counterbores:** Integrated $M$-series tapped holes into the main body, with corresponding counterbore holes projected onto the lid for recessed screw heads.
*   **Feature Projection:** Utilized the `Project` tool to transfer hole centers from the box to the lid, maintaining associativity if dimensions change.



### 3. Assembly & Mechanical Constraints
*   **As-Built & Rigid Joints:** Applied to secure the lid to the box, defining the "Closed" state of the assembly.
*   **McMaster-Carr Integration:** Standardized fasteners were imported directly into the workspace to validate thread depth and head clearance.
*   **Joint Origins:** Screws were mated to the tapped holes using cylindrical and rigid joints to ensure proper alignment and "Capture Position" integrity.




https://github.com/user-attachments/assets/4595ad92-db10-4edc-9834-3bdab6ceec8e



---

