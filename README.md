# Pet Adoption Knowledge Graph

An advanced Semantic Web project developed for **Manisa Celal Bayar University**. This project integrates multi-source pet adoption data into a unified Knowledge Graph using OWL reasoning, SHACL validation, and an LLM-powered natural language interface to facilitate semantic matching between potential adopters and shelter environments.

---

## 👥 Team Members
* **Zehra Ismayilli** - Manisa Celal Bayar University
* **Mehmet Mert Yigit** - Manisa Celal Bayar University

## 🌐 Project Deliverables & Live Links
* **WIDOCO Live Documentation & SPARQL Library:** [Click Here to View Documentation](https://zahrasmyll.github.io/pet-adoption-ontology/index-en.html)
* **Interactive WebVOWL Graph:** [Click Here to Visualize Graph](https://zahrasmyll.github.io/pet-adoption-ontology/webvowl/index.html#)

---

## 🎯 Project Objective
The main goal of this project is to bridge the semantic gap between potential pet adopters and animal shelters. By structuring pet profiles, medical backgrounds, shelter capacities, and adopter preferences (such as housing restrictions, budget constraints, and lifestyle) into a synchronized ontology, the system ensures highly accurate and ethically sound matchmaking.

### Key Features:
* **TBox Reasoner Verification:** Fully tested and checked using the HermiT Reasoner in Protégé to ensure complete logical consistency.
* **Data Integrity via SHACL:** Explicit validation shapes to enforce strict business logic (e.g., verifying that data types, age boundaries, and required relationships match system standards).
* **Intelligent Querying:** Advanced SPARQL queries involving property chains, aggregations (`COUNT`, `GROUP BY`), and logical reasoning.
* **LLM Integration Layer:** A modern workflow architecture that safely maps natural language queries into accurate SPARQL syntax.

---

## 📂 Repository Structure
```text
├── Queries/
│   └── queries.txt            # Library of raw SPARQL queries used in evaluation
├── docs/                      # Core Documentation & WIDOCO Web Deployment
│   ├── index-en.html          # Main web documentation portal (Contains SPARQL Library)
│   ├── webvowl/               # Interactive ontology visualization engine
│   ├── ProjectReport.docx     # Final Academic Project Report Document
│   ├── specification.docx     # Ontology Design Specification Document (v1)
│   ├── specification_v2.docx  # Final Ontology Design Specification Document (v2)
│   └── ...                    # WIDOCO support files and resources
├── ontology
|   ├── ontology.owl
|   ├── ontology_v2.owl        # Core OWL Ontology File (Protégé Compatible)
├── README.md                  # Project landing page and deployment guide

└── pet_adoption_shapes.ttl    # SHACL Constraints and Validation Shapes File              
```

---

## 🛠️ Installation, Setup & Usage Instructions
**1. Exploring the Knowledge Graph Locally**
To inspect, modify, or extend the core ontology file:

Download and install Protégé (v5.6.0 or higher).

Clone this repository or download pet_adoption_v2.owl.

Open Protégé, select File -> Open... and load the pet_adoption_v2.owl file.

Navigate to the Reasoner menu and select HermiT. Click Start Reasoner to execute logical inference and check consistency.

**2. Testing & Viewing SPARQL Queries**
Fast Track (Recommended): You can view all major SPARQL queries alongside their structural descriptions directly on our WIDOCO Live Documentation Page (scroll down to the Pet Adoption Ontology: SPARQL Query Library section). No installation required!

Manual Testing: Alternatively, you can copy the raw queries from the Queries/queries.txt file and execute them inside Protégé's SPARQL Query tab.

**3. Validating Constraints with SHACL**
Load the ontology file into any SHACL-compliant validator engine or use the Protégé SHACL plugin.

Run the validation shapes stored in the project files to observe data compliance and constraints testing.
