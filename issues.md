## 🏷️ SCRUM Labels Overview

Labels help organize and prioritize issues and pull requests. They make it easier to filter, track, and communicate progress during Agile development.  

### 💡 How to Use Labels

- **Estimation & Planning:** Use “Modified Fibonacci” labels to track story point complexity (0, 1, 2, 3, 5, 8, 13, 20, 40, 100, etc.).  
- **Priority & Scope:** Use “Must-have,” “Should-have,” “Could-have,” and “Won’t-have” to define deliverable priorities (MoSCoW method).  
- **Workflow:** Combine with “Brief,” “User Story,” and “Complete” to indicate progress or type.  

Each label should be applied consistently across all user stories to improve velocity tracking and sprint planning.

### 🧮 Label Reference Table

| Label | Category | Description |
|:--|:--|:--|
| **1** | Modified Fibonacci | Smallest effort, trivial fix or setup |
| **2** | Modified Fibonacci | Small, straightforward task |
| **3** | Modified Fibonacci | Moderate complexity |
| **5** | Modified Fibonacci | Medium-high complexity |
| **8** | Modified Fibonacci | High effort, multiple dependencies |
| **13** | Modified Fibonacci | Large, multi-step user story |
| **20** | Modified Fibonacci | Very large feature or integration |
| **40** | Modified Fibonacci | Epic-level or cross-project effort |
| **100** | Modified Fibonacci | Extremely large, needs to be split into smaller tasks |

### 🧩 Functional & Thematic Labels

| Label | Category | Description |
|:--|:--|:--|
| **Brief** | Workflow | Short outline or project idea |
| **Complete** | Workflow | The issue or milestone is finalized |
| **User-Story** | Workflow | Filtered & ready for iteration/sprint |
| **Theme** | General | Represents an overarching goal or project |
| **Epic** | Planning | Parent issue grouping smaller tasks |
| **Estimation** | Planning | Used for project delivery estimation |
| **dependencies** | Technical | Pull requests that update dependency files |
| **documentation** | Technical | Improvements or additions to documentation |
| **bug** | Technical | Something isn’t working |
| **wontfix** | Technical | Will not be worked on or is out of scope |

### ⚙️ Priority (MoSCoW Framework)

| Label | Priority | Description |
|:--|:--|:--|
| **Must-have** | High | Guaranteed, core, legal, or safety-critical |
| **Should-have** | Medium | Important but not vital (performance, key feature) |
| **Could-have** | Low | Desirable but not core, added if possible |
| **Won’t-have** | Excluded | Won’t be delivered in this version or iteration |

### 🧭 Example Usage

> 🏁 When estimating or organizing your backlog:
>
> - Assign **Modified Fibonacci** label to reflect story points.  
> - Add **MoSCoW priority** (e.g., “Must-have”).  
> - Tag issue type (**User Story**, **Epic**, **bug**, etc.).  
> - Optionally, include **Estimation** for release planning visibility.

### 📘 Tips

- Keep label colors consistent across repositories (e.g., Fibonacci = blue tones, MoSCoW = green/yellow/red gradient).  
- Review label usage during each sprint retrospective to improve estimation accuracy.
