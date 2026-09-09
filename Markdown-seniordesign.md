# Professional Biography

**Krrish Thakku Suresh**
B.S. Computer Science, University of Cincinnati (Aug 2022 – May 2027) | GPA: 3.6

I am a computer science student focused on machine learning, explainable AI, and applied
research. My work sits at the intersection of model performance and model interpretability —
building systems that not only predict well, but can explain *why*. Across internships and
independent projects I have worked on LLM retrieval pipelines, geometric explainability
frameworks, evolutionary optimization, and graph-based agent simulation, along with the
full-stack and data engineering work needed to make those systems usable.

---

## Contact Information

- **Email:** thakkukh@mail.uc.edu
- **Phone:** 513-923-8475
- **Location:** Cincinnati, OH
- **LinkedIn:** [linkedin.com/in/tskrrish](https://www.linkedin.com/in/tskrrish)
- **GitHub:** [github.com/tskrrish](https://github.com/tskrrish)

---

## Work Experience

### Software Engineering Intern — LogiCoy Software Technologies
*May 2024 – Aug 2024*

- Built a revenue forecasting model using a Random Forest Regressor with IQR-based outlier
  detection, cutting mean absolute error by 75% and isolating a single strongly predictive
  feature.
- Engineered a few-shot LLM prompting workflow for a document-search chatbot, reducing average
  support-query resolution time from 10 minutes to 5 through context-guided response generation.
- Developed a table question-answering pipeline with SQLAlchemy and a transformer-based table
  reasoning model (TAPEX), converting retrieved structured data into natural-language answers
  and reducing query handling time by 50%.

**Technical skills used:** Python, scikit-learn, Hugging Face Transformers, SQLAlchemy, SQL,
prompt engineering, feature selection, outlier detection, regression modeling.

**Non-technical skills used:** translating ambiguous business questions into modeling problems,
communicating model limitations to non-technical stakeholders, scoping deliverables inside a
fixed internship timeline.

### Software & Web Developer — University of Cincinnati / U.S. Environmental Protection Agency
*Aug 2024 – Dec 2024*

- Developed interactive desktop and web interfaces (Tkinter + React.js) over MySQL-backed
  MOVES4 simulation outputs to streamline visualization and analysis of environmental data.
- Automated MOVES4 data ingestion and transformation in Python + MySQL, turning raw simulation
  output into analysis-ready relational datasets and saving 3+ hours of preprocessing per
  dataset.
- Engineered a geospatial preprocessing pipeline linking roadway segment data to shapefiles,
  enabling spatial analysis and visualization of transportation simulation outputs in ArcGIS Pro.
- Built reusable Python tools for Excel-based milestone and scenario analysis, reducing manual
  data preparation time by roughly 90% per analysis cycle.

**Technical skills used:** Python, React.js, Tkinter, MySQL, ETL pipeline design, geospatial data
processing, ArcGIS Pro, data visualization.

**Non-technical skills used:** working with domain researchers who were not software engineers,
requirements gathering from scientific end users, documenting tools so others could maintain
them, prioritizing automation work by actual time saved.

---

## Other Relevant Work Experience

### Peer Teaching Assistant — ENED 1120: Design Thinking II, University of Cincinnati
*Jan 2024 – Dec 2024*

- Mentored 72 undergraduate engineering students across Visual Basic, MATLAB, LabVIEW, and
  Excel, providing guidance on programming, data analysis, and engineering problem-solving.
- Led bi-weekly technical mentoring sessions for groups of 15–20 students, debugging student
  implementations and reinforcing programming fundamentals.
- Evaluated programming assignments, exams, and LEGO EV3 robotics projects, giving targeted code
  and design feedback and working with instructors to identify recurring learning gaps.

**Skills used:** technical communication, debugging under time pressure, mentoring, MATLAB,
LabVIEW, Visual Basic, Excel, collaboration with faculty.

---

## Selected Projects

**Geometric Prototype-Rule Explainability for Black-Box Models** *(May 2026 – Jul 2026)*
Built an explainability framework using PCA, Delaunay triangulation, and barycentric coordinates
to express black-box predictions as sparse mixtures of data-derived prototype rules. Designed
separate coverage and fidelity metrics, reaching ~92% coverage while capturing a ~10× change in
fidelity error under controlled noise, and validated across the Body Fat, Wine, IRIS, Wheat, Seed, Steel Defect, and
Concrete Strength datasets. The framework abstains explicitly on samples outside the learned
prototype hull.

**Explainable Adaptive Mutation Control for Genetic Algorithms** *(Apr 2026 – May 2026)*
Architected an adaptive genetic algorithm for job-shop scheduling that uses a 9-rule fuzzy
inference system to control mutation rate from population diversity and search stagnation, while
emitting plain-English explanations for each decision. Benchmarked fuzzy, crisp-rule, and static
strategies over 15-run experiments on Fisher–Thompson FT06/FT10, reaching the optimal FT06
makespan of 55.

**Evolving Agents – Evolutionary Dynamics on Belief Graphs** *(Jan 2026 – Apr 2026)*
Developed a graph-based agent simulation representing beliefs as valued nodes and associations as
weighted edges, with thought modeled as probabilistic traversal under first-visit payoff. Found
that hard stall interventions maximized payoff but collapsed behavioral variance to zero while
soft nudges preserved diversity; graph crossover with fitness-proportional selection raised mean
population fitness by ~70%.

---

## Technical Skills

| Category | Tools |
| --- | --- |
| **Languages** | Python, C/C++, JavaScript, SQL, MATLAB |
| **ML / AI** | PyTorch, scikit-learn, Hugging Face Transformers, LangChain, Chemprop, RDKit |
| **Data** | NumPy, Pandas, SciPy, NetworkX |
| **Web & Backend** | React.js, FastAPI, SQLAlchemy, MySQL, PostgreSQL, Amazon Aurora |
| **Cloud & Tooling** | AWS Lambda, AWS Amplify, Docker, Git |
| **Concepts** | Machine learning, deep learning, explainable AI, generative AI, LLMs, NLP, graph neural networks, information retrieval, search & ranking, genetic algorithms, fuzzy logic, evolutionary computation, data structures & algorithms |

---

## Project Sought

I am looking for a capstone project centered on AI/ML pipelines where interpretability is part
of the requirement, not an afterthought. The projects I have enjoyed most involved taking a
model that already worked and making its reasoning legible — through prototype rules, fuzzy
explanations, or structured intermediate representations. I would like a capstone that continues
in that direction.

Concretely, I want to build the full pipeline rather than an isolated model: data ingestion and
preprocessing, feature and representation design, training and hyperparameter search, a rigorous
evaluation harness, and reproducible experiment tracking, with the model served behind an API or
interface so results are actually usable.

**A research paper is an goal for me.** I would like the capstone to produce results
strong enough to submit to a conference or workshop, and I'm willing to do the work that takes 
— a clear new idea, honest comparisons against the best existing methods, enough repeated runs 
to trust the numbers, and code released so others can reproduce it. My three most recent projects
were all structured this way — defined metrics, controlled experiments, multi-run benchmarks. 
I would especially value a faculty advisor willing to co-author and target a specific venue and 
deadline from the start.

Specific directions I would be glad to work on:

- **Explainable AI tooling.** A library, dashboard, or evaluation harness that makes black-box
  model behavior inspectable, including honest handling of cases where a model should abstain
  rather than explain.
- **LLM-backed retrieval and question answering.** Systems that answer questions over
  heterogeneous sources — documents, tables, relational data — with traceable citations back to
  the retrieved evidence.
- **Graph-based modeling.** Graph neural networks or graph algorithms applied to a real domain
  such as scientific data, transportation networks, or knowledge graphs.
- **Optimization and search.** Evolutionary or heuristic optimization for scheduling, resource
  allocation, or design-space exploration, particularly where the search process itself needs to
  be explainable to a human operator.
- **Research-adjacent work with a real dataset.** Projects sponsored by a lab, industry partner,
  or agency where the data is messy and the evaluation criteria are genuine.

**What I would contribute to a team:** end-to-end ownership of the modeling and data pipeline —
ingestion, preprocessing, model design, evaluation methodology — plus the front-end and API work
needed to make results usable. I am comfortable explaining technical
decisions to people outside the immediate project.
