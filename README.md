# How Characteristics Shape Costs and Benefits in B2B Data Sharing Initiatives

This repository contains the dataset accompanying the master's thesis *How Characteristics Shape Costs and Benefits in B2B Data Sharing Initiatives*, submitted to the Faculty of Engineering and Architecture, Ghent University, in the programme Industrial Engineering and Operations Research (Manufacturing and Supply Chain Engineering).

## About the thesis

Business-to-business (B2B) data sharing is increasingly important for organizations seeking operational efficiency, regulatory compliance, and supply chain transparency under European regulatory frameworks. However, limited research systematically examines how the structural characteristics of data sharing platforms and ecosystems relate to the specific costs and benefits experienced by participating organizations across different industries. This thesis addresses that gap by developing and applying two complementary taxonomies to a dataset of 100 B2B data sharing initiatives across six sectors.

The main research question is:

> *How do structural characteristics of B2B data sharing initiatives relate to the different types of costs and benefits of data sharing across different industries under European regulatory frameworks?*

## Dataset overview

The dataset comprises 100 B2B data sharing initiatives selected through a structured search of academic literature, EU project documentation, industry reports, and existing taxonomies. Each case satisfies seven inclusion criteria including focus on B2B data exchange, actual data sharing between independent parties, identifiable governance mechanisms, and sufficient publicly available documentation.

| Sector                             | Total | Platforms | Ecosystems |
| ---------------------------------- | ----- | --------- | ---------- |
| Agri-food                          | 21    | 16        | 5          |
| Multi-sector                       | 19    | 12        | 7          |
| Sustainability & carbon accounting | 15    | 9         | 6          |
| Mobility                           | 14    | 5         | 9          |
| Pharmaceutical                     | 13    | 8         | 5          |
| Supply chain networks              | 11    | 9         | 2          |
| Manufacturing & automotive         | 7     | 2         | 5          |
| **Total**                          | **100** | **61**  | **39**     |

## The two taxonomies

**Taxonomy 1 — Structural Classification.** Classifies initiatives based on their structural characteristics across 6 meta-dimensions (Governance and control, Value creation and use, Market structure and interaction, Pricing logic, Organization, Service medium), 14 dimensions, and 50 characteristics.

**Taxonomy 2 — Value Offering and Realization.** Captures the concrete cost-benefit mechanisms delivered to participants. Structured along two axes (offering vs. realization, provider vs. consumer), it contains 4 meta-dimensions, 18 dimensions, and 74 characteristics.

Both taxonomies were developed following the iterative method of Nickerson et al. (2013), as refined by Kundisch et al. (2022).

## Repository contents

- `Dataset_final.xlsx` — the full dataset, containing four sheets:
  - **Set list of cases** — the 100 cases with sector and initiative type (platform or ecosystem)
  - **Criteria** — case inclusion criteria
  - **Mapping 1st taxonomy** — coding of each case against Taxonomy 1
  - **Mapping 2nd taxonomy** — coding of each case against Taxonomy 2
- `README.md` — this file

## How the data was coded

Each case was coded by a single researcher against all dimensions of both taxonomies using publicly available sources (websites, technical documentation, white papers, academic publications, EU project deliverables, industry reports). A conservative coding approach was applied: characteristics were coded *Yes* only when positive evidence was identified, and *No* otherwise. This approach systematically underrepresents undocumented mechanisms but reduces the risk of overstatement.

## Citation

If you use this dataset, please cite the master's thesis:

> Vanhandsaeme, D. (2026). *How Characteristics Shape Costs and Benefits in B2B Data Sharing Initiatives*. Master's thesis, Faculty of Engineering and Architecture, Ghent University.

## Supervisors and counsellor

- Prof. dr. ir. Sofie Verbrugge (supervisor)
- Prof. dr. ir. Didier Colle (supervisor)
- Maarten de Mildt (counsellor)

## License

This dataset is released for academic and research use. Please contact the author for other uses.
