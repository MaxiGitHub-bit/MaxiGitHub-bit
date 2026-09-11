## Victor Okeke

Data and infrastructure. I build systems end to end, from ingestion and warehouse design through to the layer people actually read.

Background runs from applied electrical engineering into network engineering, then cybersecurity and now data. Currently finishing an MSc in Data Analytics and moving into dissertation. 

**MSc Data Analytics** (in progress) · **MSc Cybersecurity** · **Advanced Diploma in Network Engineering · **Applied Electrical Engineering**

Open to data engineering, analytics, and security engineering or analyst roles.

Currently finishing coursework and moving into dissertation. Open to security engineer, threat research, security analyst, data engineering and analytics roles.

---

### What I work with

**Data engineering** · SQL Server · SSIS · dimensional modelling (Kimball) · ETL pipeline design
**Analytics and BI** · Tableau · SSRS · Python · Pandas
**Machine Learning** · scikit-learn · CNNs and transfer learning · PCA and LDA
**other** · Neo4j and Cypher · Git

---

### Select work

**[Energy Intelligence Data Warehouse](https://github.com/MaxiGitHub-bit/energy-intelligence-data-warehouse)**
A governed dimensional warehouse over 159,739 rows of IEA monthly electricity statistics spanning 194 months and 48 countries. Star schema, SSIS ETL across a three-layer database architechture, four SSRS reports and a four-visual Tableau dashboard. Includes a SQL Server versus Neo4J retrieval benchmark across seven matched query pairs.

My electrical engineering background shaped the model here: the product dimension
separates renewable classification from intermittency and dispatchability, because those are different questions. Hydro is renewable and dispatchable, solar is renewable and intermittent, nuclear is neither. Most models collapse them.

The part I would point at: the source interleaves pre-aggregated rollup rows at the same grain as leaf rows, so an unfiltered SUM overstated production by roughly eightfold. I measured it at 3.01x on a single country-month, then fixed it structurally with metadata flags and a governed view layer rather than patching it in the reports.

**[Mortgage Savings Simulator](https://github.com/MaxiGitHub-bit/mortgage-savings-simulator)**
Deterministic savings-accumulation model in Python. Three scenarios, with bisection search used to solve for the minimum savings rate that meets a fixed deadline.

---

### Elsewhere

- **Tableau Public** · https://public.tableau.com/app/profile/victorokeke/vizzes
- **LinkedIn** · https://www.linkedin.com/in/victor-okeke-g/
