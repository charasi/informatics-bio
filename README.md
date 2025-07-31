# 🧬 BioInformatics: Universal Metabolite Database

**BioInformatics** is a robust web-based platform developed during my capstone at **UW–Madison**, designed to help researchers explore, redesign, and analyze metabolic pathways across multiple organisms. It integrates curated genome-scale models with advanced graph search logic and role-based data management to drive biological insights.

---

## 📦 Dataset Summary

- 🌐 Models: 20 BiGG genome-scale networks
- 🧪 Entities:
    - 14,000 metabolites
    - 25,000 reactions
    - 10,000 genes
    - 8,000 compounds
- 🔄 Transformation: JSON → MySQL schema via custom Python and Java tools

---

## 🔎 Key Functionalities

| Feature                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 🔍 Gene/Reaction/Metabolite Search | Intuitive search interfaces for navigating complex biological datasets     |
| 🔁 Dynamic Pathway Discovery  | BFS + MySQL query engine for tracing metabolic pathways, including cycles |
| 💬 Collaborative Commenting   | Registered users can annotate entries to foster community engagement       |
| 🔧 Admin Control Portal       | Secure interface for creating, updating, and deleting database entries     |
| 🛡️ Role-Based Access         | Session login with role validation to protect modification endpoints       |

---

## 🧠 Pathway Discovery Logic

Combines:
- **Breadth-First Search** for shortest-path resolution
- **SQL join trees** to connect metabolites across reactions
- **Cycle detection** for handling feedback loops in metabolic networks

---

## 💻 Technologies Used

| Tool/Framework     | Role                                              |
|--------------------|---------------------------------------------------|
| **Python**         | Data parsing, backend utilities                   |
| **Java**           | JSON transformation pipeline                      |
| **MySQL**          | Relational schema for genome-scale models         |
| **HTML/CSS/JS**    | Interactive web interface                         |
| **Session Auth**   | Role-based user protection and secure endpoints   |

