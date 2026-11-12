# UniData/UEL — Data Lakehouse Engineering, Architecture & Governance

**Institutional Data Engineering · Data Architecture · Analytics Engineering · DataOps · Research & Development**

**Personal Engineering Case Study | 2026**

**Eduardo Fernandes Bueno**  
Data Engineer | Data Scientist | M.Sc. Candidate in Computer Science  
Research & Development — Information Technology Office (ATI/UEL)  
State University of Londrina (UEL), Brazil

**Core Technologies:** Python · SQL · Oracle Database · Apache Airflow · Apache Spark · PySpark · MinIO · Apache Parquet · Dremio · Qlik · Docker · GitLab CI/CD

**Engineering Practices:** Data Lakehouse · Medallion Architecture · ETL/ELT · Data Quality · Data Contracts · Idempotency · Data Governance · Data Lineage · DataOps · Scientific Reproducibility

[Professional Portfolio](https://eduardofernandesbueno.github.io/) | [GitHub Profile](https://github.com/eduardofernandesbueno) | [LinkedIn](https://www.linkedin.com/in/eduardofernandesbueno/) | [ATI/UEL](https://sites.uel.br/ati/estrutura-e-equipe/)

---

## 1. Executive Summary

**Engineering institutional data systems. Building trustworthy analytical foundations. Connecting software engineering, data architecture, and scientific research.**

This repository presents a professional case study of my contributions to the **UNIDATA — UEL Data Platform**, an institutional Data Lakehouse research and engineering initiative at the State University of Londrina (UEL), Brazil.

The project is associated with the university's Information Technology Office (ATI/UEL) and the broader initiative to improve academic data integration and management across public universities in Paraná, Brazil.

My work contributes to the design, implementation, technical validation, documentation, and governance of institutional data engineering workflows.

The 2026 development cycle established and validated an initial Data Lakehouse MVP using authorized institutional reference data.

The documented work encompasses:

- Institutional data integration.
- Workflow orchestration.
- Batch data ingestion.
- ETL/ELT pipeline development.
- Layered analytical data architecture.
- Distributed data processing.
- Data modeling and semantic transformation.
- Data quality assurance.
- Data contracts and schema validation.
- Technical metadata and traceability.
- Idempotent execution and controlled reprocessing.
- SQL-based analytical data serving.
- Business Intelligence integration.
- Version control and CI validation.
- Engineering documentation.
- Collaborative technical review.
- Data governance and privacy-aware processing.

**Validation status:** The MVP achieved documented end-to-end functional validation in a controlled local development environment during 2026. This is distinct from formal institutional production deployment and certification, which are not claimed here.

**Repository scope:** Public-safe professional documentation only. No institutional source code, datasets, internal infrastructure details, credentials, operational logs, or confidential artifacts are included.

---

## 2. Project at a Glance

| Attribute | Description |
|---|---|
| Project | UNIDATA — UEL Data Platform |
| Institution | State University of Londrina (UEL), Brazil |
| Institutional Unit | Information Technology Office (ATI/UEL) |
| Year | 2026 |
| Professional Role | Master's Scholarship Holder (Computer Science) |
| Activity | Research & Development / Data Engineering |
| Architecture | Data Lakehouse |
| Processing Model | Layered batch data processing |
| Storage Approach | S3-compatible object storage and Parquet |
| Data Organization | Landing, Bronze, Silver, Gold |
| Data Serving | SQL analytical access and BI integration |
| Engineering Approach | Incremental delivery and technical validation |
| Development Practices | Git, GitLab, code review, CI checks and documentation |
| Validated Scope | Controlled institutional reference-data pilot |
| Public Artifact | Personal documentation-only case study |

The platform is a collaborative institutional initiative. The responsibilities and contributions described here should not be interpreted as exclusive authorship or ownership of the platform.

---

## 3. The Engineering Challenge

Higher education institutions operate multiple information systems supporting academic, administrative, and institutional activities.

These systems typically maintain operational data designed for transactional requirements rather than integrated analytical consumption.

The resulting engineering challenges can include:

- Heterogeneous relational data sources.
- Inconsistent data representations.
- Different data types and schemas.
- Limited cross-system integration.
- Repeated manual extraction.
- Difficulties reproducing analytical datasets.
- Insufficient processing traceability.
- Data quality inconsistencies.
- Unclear analytical definitions.
- Security and privacy constraints.
- Uncontrolled transformations.
- Limited confidence in reported indicators.

A reliable analytical platform must address these issues before institutional information can be confidently reused.

### Our Engineering Focus

The UNIDATA MVP investigated and implemented a governed data processing foundation that separates ingestion, transformation, data quality, analytical modeling, and consumption.

The objective was not merely to move data between systems.

It was to establish a **traceable, reproducible, and governed analytical workflow** suitable for controlled institutional development.

---

## 4. My Role and Responsibilities

I participated in the project as an M.Sc. scholarship holder in Computer Science associated with ATI/UEL.

My activities combined technical implementation, architecture-related work, quality validation, documentation, and collaborative engineering coordination.

### Data Engineering

- Contributing to relational data ingestion workflows.
- Working with Python-based processing routines.
- Participating in Apache Airflow DAG development and validation.
- Working with batch transformation processes.
- Supporting structured analytical dataset preparation.
- Investigating and validating reprocessing behavior.

### Data Architecture

- Working with the Data Lakehouse architectural approach.
- Supporting the separation of ingestion, storage, processing, and analytical consumption.
- Contributing to layered data organization.
- Working with data modeling and semantic transformation.
- Evaluating consistency across processing stages.

### Data Quality and Governance

- Supporting schema and quality checks.
- Reviewing processing evidence.
- Working with data contracts and traceability requirements.
- Supporting controlled reprocessing and idempotency.
- Applying data minimization and privacy-aware processing considerations.
- Documenting technical validation and limitations.

### Software Engineering and DataOps

- Working with Git and institutional GitLab workflows.
- Supporting Merge Request review and integration practices.
- Participating in CI-related verification.
- Maintaining technical documentation.
- Supporting incremental development and acceptance criteria.
- Contributing to collaboration and technical guidance within the development team.

These activities were undertaken within a collaborative institutional project under the applicable technical supervision and governance.

---

## 5. Technology Stack

The technologies below are organized according to their documented role and implementation maturity.

### 5.1 Core Data Engineering Stack

| Technology | Engineering Application |
|---|---|
| Python | Pipeline development, automation and validation |
| SQL | Relational data access and analytical queries |
| Oracle Database | Authorized institutional relational source |
| Apache Airflow | Workflow orchestration and DAG execution |
| Apache Spark | Data processing and transformation |
| PySpark | Python-based Spark transformations |
| MinIO | S3-compatible object storage |
| Apache Parquet | Columnar analytical storage |
| Dremio | SQL-based analytical data serving |
| Qlik | Analytical visualization and BI validation |

These technologies formed part of the documented engineering and validation workflow.

Their inclusion does not imply that every component was independently implemented or administered by the case-study author.

### 5.2 Development and DataOps Stack

| Technology | Engineering Application |
|---|---|
| Docker | Containerized development environments |
| Docker Compose | Local service orchestration |
| Git | Distributed source version control |
| GitLab | Institutional collaboration and repository management |
| GitLab CI/CD | Integration checks and validation workflows |
| GitLab Issues / Milestones | Work tracking and delivery organization |
| Merge Requests | Code review and controlled integration |
| Visual Studio Code | Development and source inspection |
| Python virtual environments | Dependency and environment isolation |
| pytest | Targeted automated verification |

### 5.3 Supporting Laboratory Infrastructure

The initial technical environment also included:

| Technology | Documented Role |
|---|---|
| PostgreSQL | Supporting metadata persistence |
| Redis | Task messaging and orchestration support |
| Jupyter | Interactive data exploration environment |
| Metabase | Experimental Business Intelligence environment |
| Grafana | Observability experimentation |
| OpenMetadata | Metadata governance environment |

These services were documented as part of the initialized or explored development infrastructure.

**Important distinction:** Their presence in the laboratory environment does not establish that they were fully integrated into, or operationally validated as part of, the final institutional MVP.

The validated BI direction for the documented 2026 MVP used **Qlik**, with Dremio providing analytical SQL access.

### 5.4 Engineering Concepts and Methods

The work also involved:

- Data Lakehouse architecture.
- Medallion Architecture.
- ETL and ELT.
- Batch ingestion.
- Distributed data processing.
- Schema evolution considerations.
- Data type normalization.
- Deduplication.
- Dimensional data modeling.
- Semantic modeling.
- Data contracts.
- Data quality validation.
- Dataset traceability.
- Metadata management.
- Idempotency.
- Controlled reprocessing.
- Data lineage documentation.
- CI validation.
- Technical acceptance criteria.
- Data governance.
- Privacy-aware software engineering.
- Reproducible analytical workflows.

---

## 6. Data Lakehouse Architecture

The MVP followed a layered Data Lakehouse architecture.

The conceptual data lifecycle can be summarized as:

**Authorized Data Sources → Orchestrated Ingestion → Governed Raw Storage → Data Transformation → Curated Analytical Data → SQL Serving → Business Intelligence**

This is a generic engineering abstraction and does not reproduce internal infrastructure topology.

### 6.1 Landing Layer

The Landing layer supported the controlled reception of source data and technical processing information.

Its purpose was to establish a traceable boundary between the source systems and downstream analytical processing.

### 6.2 Bronze Layer

The Bronze layer supported governed persistence of ingested data.

Key concerns included:

- Preservation of source-oriented structure.
- Consistent storage representation.
- Technical metadata.
- Processing traceability.
- Reproducible ingestion.
- Controlled reprocessing.

Apache Parquet was used for analytical data persistence.

### 6.3 Silver Layer

The Silver layer supported data preparation and quality-oriented transformations.

The documented development included:

- Data type normalization.
- String normalization.
- Schema validation.
- Deduplication.
- Consistency checks.
- Controlled transformation execution.
- Technical processing evidence.

Apache Spark and PySpark were used for data transformations.

### 6.4 Gold Layer

The Gold layer supported curated analytical structures.

The work included:

- Analytical data modeling.
- Dimension-oriented representations.
- Aggregated datasets.
- Data contracts.
- Semantic definitions.
- Preparation for SQL analytical consumption.

The implemented scope was limited to authorized institutional reference-data domains.

### 6.5 Analytical Serving

Dremio supported SQL-based analytical access, while Qlik was used in the documented BI validation.

This completed the functional demonstration of the local analytical workflow.

**Architectural principle:** Each layer has a distinct responsibility, making transformations easier to validate, explain, troubleshoot, and audit.

---

## 7. Data Ingestion Engineering

The initial engineering workflow integrated authorized relational data into the analytical environment.

### Documented Capabilities

- Controlled source selection.
- Workflow orchestration.
- Repeatable extraction.
- Structured analytical storage.
- Technical metadata generation.
- Ingestion validation.
- Controlled reprocessing.

The ingestion work involved Python, SQL, Oracle Database, Apache Airflow, MinIO, and Parquet.

### Engineering Considerations

Reliable ingestion requires more than successful data extraction.

It must also account for:

- Source consistency.
- Schema compatibility.
- Processing boundaries.
- Failure handling.
- Duplicate execution.
- Recovery and reprocessing.
- Auditability.
- Data protection.

The project addressed these concerns within the validated pilot scope.

---

## 8. Data Transformation with Apache Spark

Data transformation was a central part of the UNIDATA MVP.

The work involved processing data from an ingested analytical representation into more consistent and structured datasets.

### Transformation Concerns

- Normalizing data types.
- Standardizing textual representations.
- Validating expected fields.
- Detecting inconsistencies.
- Handling duplicate records.
- Preparing analytical relationships.
- Producing structured outputs.
- Recording transformation evidence.

### Spark and PySpark

Apache Spark provided the processing framework for transformation workloads.

PySpark enabled Python-based engineering and development of transformation logic.

The use of a distributed processing framework was part of the platform's technical design.

This case study does not claim independently measured distributed scalability, production throughput, or performance improvements.

---

## 9. Data Quality Engineering

The project incorporated data quality checks to support dependable analytical processing.

### Quality Dimensions

The documented work addressed engineering concerns such as:

**Schema consistency**

Checking whether datasets conform to expected structural definitions.

**Data completeness**

Investigating missing or incomplete information.

**Data type correctness**

Checking compatibility between expected and observed data types.

**Consistency**

Verifying relevant relationships and transformation outputs.

**Uniqueness and duplication**

Identifying and handling duplicate representations where applicable.

**Processing integrity**

Ensuring that outputs correspond to controlled execution contexts.

### Data Contracts

The development included contracts and validation rules supporting consistency across data layers.

These controls helped establish explicit technical expectations for analytical datasets.

### Validation Evidence

Quality checks and technical processing records supported the assessment of whether specific processing stages met the pilot's acceptance criteria.

No confidential validation reports, rule definitions, or institutional measurements are reproduced here.

---

## 10. Idempotency and Controlled Reprocessing

One important engineering requirement was ensuring that repeated execution would not unintentionally compromise analytical consistency.

### Idempotency

Idempotent processing was addressed to support repeatable workflow execution.

### Reprocessing

The project investigated controlled reprocessing rather than unrestricted overwriting.

### Expected Engineering Behavior

The processing design distinguished normal execution, handling of previously processed inputs, and explicitly requested reprocessing.

### Why It Matters

These controls contribute to:

- Reproducibility.
- Recovery from partial failures.
- Predictable pipeline behavior.
- Reduced duplication.
- Safer maintenance.
- More reliable analytical outputs.

The behavior was validated within the documented development and homologation scope.

---

## 11. Analytical Modeling and Analytics Engineering

The UNIDATA MVP also addressed the transition from technically processed data to analytically meaningful datasets.

### Engineering Activities

- Defining analytical representations.
- Organizing curated data.
- Supporting dimensional modeling.
- Establishing semantic consistency.
- Documenting data contracts.
- Preparing structured analytical outputs.
- Exposing curated data through SQL-based serving.

### Data Products

The project developed the technical foundation for a governed academic analytical data product.

However, formal institutional data product certification is a separate governance milestone.

The case study does not claim that the data product had received final institutional certification.

### Analytics Engineering Perspective

The work illustrates the relationship between:

**Data Integration → Data Transformation → Analytical Modeling → Data Quality → Governed Consumption**

This approach emphasizes data trustworthiness and semantic consistency rather than dashboard construction alone.

---

## 12. SQL Analytics and Business Intelligence

The documented MVP included the integration of curated analytical data with SQL-based serving and BI visualization.

### Dremio

Dremio was used as an analytical SQL access layer.

The work addressed:

- Analytical dataset access.
- Query-oriented consumption.
- Serving curated data.
- Validation of accessible analytical outputs.

### Qlik

Qlik was used for the documented BI and visualization workflow.

The validated scope included the ability to consume curated analytical information and visualize aggregated results.

### Scope of Validation

This integration supported the end-to-end technical validation of the pilot in a controlled environment.

It should not be interpreted as evidence of a fully certified university-wide reporting platform, institution-wide metric governance, or permanent production availability.

---

## 13. DataOps, GitLab and CI/CD

Reliable institutional data engineering requires disciplined software delivery practices.

The project used Git and GitLab to support collaborative development, review, and integration.

### Documented Practices

- Distributed version control.
- Development branches.
- Merge Request workflows.
- Peer review.
- Technical documentation.
- Issues and milestones.
- Incremental delivery.
- CI validation.
- Automated checks.
- Preservation of validated baselines.
- Controlled promotion of changes.

### Continuous Integration

The documented CI-related work included technical checks and safeguards intended to reduce integration errors.

Specific activities involved syntax validation, test execution, controlled planning workflows, and checks designed to prevent unsafe automated operations.

### DataOps Principles

The work applied DataOps-oriented concepts such as:

- Repeatable pipelines.
- Controlled changes.
- Validation before integration.
- Technical traceability.
- Automated verification where applicable.
- Collaborative review.
- Clear acceptance criteria.
- Separation between development validation and release approval.

**Important:** GitLab CI validation does not, by itself, prove that production deployment or continuous delivery to institutional servers was completed.

---

## 14. Infrastructure and Reproducible Development

The development process involved containerized laboratory environments using Docker and Docker Compose.

### Engineering Benefits

Containerization supported:

- Repeatable environment initialization.
- Separation of technical services.
- Dependency isolation.
- Development experimentation.
- Troubleshooting.
- Integration verification.

The laboratory included orchestration, storage, processing, analytical access, and supporting infrastructure components.

### Operational Boundaries

The development environment was distinct from a formally approved institutional production deployment.

The case study does not publish:

- Hostnames.
- Internal network topology.
- Port mappings.
- Server specifications.
- Access-control configurations.
- Storage identifiers.
- Internal deployment instructions.
- Production configuration.

No claim is made regarding high availability, disaster recovery certification, or institution-wide production readiness.

---

## 15. Data Governance, Privacy and LGPD

Data governance was treated as an engineering requirement throughout the MVP.

The work involved controls and practices related to:

- Authorized data-source selection.
- Data minimization.
- Processing scope restrictions.
- Data quality.
- Technical metadata.
- Traceability.
- Documented transformations.
- Access-control considerations.
- Privacy-aware data processing.
- Auditable engineering changes.

### Privacy by Design

The MVP included preventive controls intended to exclude personal-data domains outside the approved pilot scope.

This demonstrates the practical relevance of privacy requirements to data engineering design.

### Brazilian LGPD

Brazil's General Data Protection Law (LGPD) provides an important regulatory context for institutional data processing.

My academic and professional background in Law also informs my interest in:

- Data protection.
- Information governance.
- Regulatory compliance.
- Responsible data processing.
- Privacy-aware system design.
- Responsible AI.

**Compliance limitation:** Technical safeguards and privacy-aware design practices should not be interpreted as an independent legal compliance certification of the UNIDATA platform.

---

## 16. Engineering Validation — 2026

The project followed an incremental engineering and validation process.

The documented MVP activities progressed through ingestion, transformation, analytical modeling, SQL access, and BI validation.

### Validated Technical Scope

| Engineering Capability | Documented Outcome |
|---|---|
| Controlled relational ingestion | Implemented and technically validated |
| Layered analytical storage | Implemented within the pilot scope |
| Bronze-to-Silver transformation | Implemented and validated |
| Curated analytical structures | Implemented within the MVP |
| Data contracts and quality checks | Developed and validated within defined scope |
| Idempotency and reprocessing | Tested in controlled workflows |
| SQL analytical access | Validated through Dremio |
| BI analytical consumption | Validated through Qlik |
| Local end-to-end workflow | Functional validation documented in 2026 |
| Institutional production deployment | Not established by the available evidence |
| Formal data product certification | Not claimed |

### Understanding the Validation Boundary

Three engineering milestones must be distinguished:

1. **Functional validation:** Demonstrating that the defined workflow performs as expected in the controlled validation environment.
2. **Release approval:** Formal acceptance of a specific version for institutional delivery.
3. **Operational deployment:** Installation and validation within the authorized institutional operating environment.

Successful functional validation does not automatically establish release approval or production deployment.

### Evidence-Based Reporting

This case study does not report confidential:

- Record counts.
- Database sizes.
- Institutional indicators.
- Pipeline execution times.
- Performance benchmarks.
- Internal quality measurements.
- Production service metrics.

No quantitative results have been invented for portfolio presentation.

---

## 17. Research & Development Context

My professional work at ATI/UEL is connected to my M.Sc. studies in Computer Science at UEL.

My research interests include:

- Data Engineering.
- Data Architecture.
- Applied Machine Learning.
- Educational Data Mining.
- Learning Analytics.
- Higher Education Analytics.
- Data Governance.
- Scientific Reproducibility.
- Evidence-based Decision Support.

### Research Motivation

Reliable Machine Learning systems depend on reliable data foundations.

Before building analytical or predictive models, researchers and engineers must address:

- Data provenance.
- Quality.
- Schema consistency.
- Reproducibility.
- Temporal integrity.
- Data leakage.
- Governance.
- Evaluation methodology.

The UNIDATA engineering experience provides practical context for investigating how governed data architectures can support trustworthy analytical research.

### Relationship to Machine Learning

The documented UNIDATA MVP focused on data platform engineering and analytical infrastructure.

It should not be confused with a deployed institutional Machine Learning model for individual student dropout prediction.

Predictive modeling research is documented separately from the platform's validated operational scope.

---

## 18. Related Scientific Publication

### Brazilian Higher Education Dropout — SBIE 2026

**Published research:**

*Evasão no Ensino Superior brasileiro: Mapeamento Estruturado da Literatura em ML, EDM e LA, e Benchmark.*

**Authors:**

Eduardo Fernandes Bueno, Decio Wey Berti Junior, and Jacques Duílio Brancher.

**Conference:** 37th Brazilian Symposium on Informatics in Education (SBIE 2026).

**DOI:** https://doi.org/10.5753/sbie.2026.27263

**Supplementary Research Artifacts:**

https://github.com/eduardofernandesbueno/sbie2026-evasao-ensino-superior-artefatos

This scientific work investigates higher education dropout through structured literature mapping and a temporal Machine Learning benchmark based on public INEP/MEC data.

The publication and its supplementary artifacts constitute a separate research contribution.

The benchmark must not be represented as a production Machine Learning service implemented through UNIDATA.

---

## 19. Technical Skills Demonstrated

The project provides documented experience relevant to several engineering disciplines.

### Data Engineer

- Data ingestion.
- Batch processing.
- Data pipelines.
- ETL/ELT.
- Workflow orchestration.
- Apache Airflow.
- Apache Spark.
- PySpark.
- Python.
- SQL.
- Parquet.
- Data quality.
- Idempotency.
- Reprocessing.

### Data Architect

- Data Lakehouse.
- Layered data architecture.
- Medallion Architecture.
- Data modeling.
- Data contracts.
- Analytical serving.
- Data governance.
- System integration.
- Architectural documentation.

### Analytics Engineer

- Data transformation.
- Curated analytical datasets.
- Dimensional modeling.
- Semantic consistency.
- SQL analytics.
- Data quality.
- BI integration.
- Dremio.
- Qlik.

### DataOps / Software Engineer

- Git.
- GitLab.
- CI validation.
- Merge Requests.
- Peer review.
- Docker.
- Docker Compose.
- Automated testing.
- Controlled integration.
- Technical documentation.
- Reproducibility.

### Applied Researcher

- Scientific methodology.
- Applied Computer Science.
- Analytical research.
- Research documentation.
- Reproducibility.
- Privacy-aware data engineering.
- Educational data analytics.

These skill categories describe documented work and technical experience, not certification or employment at a specific seniority level.

---

## 20. Engineering Lessons

The experience reinforced several important principles.

### Reliable Data Engineering Requires Explicit Boundaries

Ingestion, transformation, modeling, and consumption should have clearly defined responsibilities.

### Data Quality Must Be Part of the Pipeline

Quality validation cannot be treated solely as a final reporting activity.

### Reprocessing Must Be Predictable

Repeatability, idempotency, and processing traceability are fundamental to reliable analytical workflows.

### Data Governance Begins During Ingestion

Privacy, metadata, scope restrictions, and validation should be considered from the beginning of the data lifecycle.

### Software Engineering Practices Matter in Data Platforms

Data pipelines benefit from code review, controlled releases, automated verification, and documentation.

### Functional Validation Is Not Production Deployment

A working local MVP demonstrates technical feasibility, but deployment readiness requires additional operational evidence.

### Architecture Must Be Supported by Evidence

Architecture diagrams and planned components are not substitutes for implemented, tested, and validated behavior.

---

## 21. Current Scope and Limitations

This case study documents a validated engineering MVP and related development activities from 2026.

It does **not** claim:

- Full production deployment across UEL.
- Institution-wide data-source integration.
- Formal institutional certification of all analytical outputs.
- A fully operational enterprise Data Catalog.
- Complete integration of every laboratory service.
- Independently validated production scalability.
- Continuous production availability.
- An institutionally deployed predictive dropout model.
- End-to-end implementation of every component described in broader architectural planning.

The engineering work should be evaluated according to its actual implemented and validated scope.

---

## 22. Public Documentation and Confidentiality

This is intentionally a **documentation-only repository**.

It does not contain:

- Institutional source code.
- Production configurations.
- Internal architectural diagrams.
- Database schemas.
- Table or column names.
- Dataset samples.
- Internal file paths.
- Storage bucket identifiers.
- Infrastructure addresses.
- Credentials or tokens.
- CI/CD configuration files.
- Operational logs.
- Confidential quality reports.
- Internal Merge Request discussions.
- Private administrative documents.
- Personal or student-level data.
- Confidential performance measurements.

The information presented is limited to professional responsibilities, general engineering concepts, documented technologies, and non-sensitive descriptions of the validated MVP.

### Reproducibility Note

This repository is not an executable reproduction of the institutional platform.

Its objective is to document professional engineering experience and explain the technical scope without redistributing protected institutional assets.

---

## 23. Authorship and Institutional Disclaimer

This repository is a personal professional case study prepared and maintained by Eduardo Fernandes Bueno.

The UNIDATA platform is a collaborative institutional initiative involving multiple contributors, technical teams, university stakeholders, and academic supervision.

This repository:

- Is not the official UNIDATA software repository.
- Is not a redistribution of institutional software.
- Does not claim exclusive project authorship.
- Does not claim ownership of institutional data or infrastructure.
- Does not represent an official statement by ATI/UEL.
- Does not imply institutional endorsement of this personal portfolio.
- Does not grant rights to reproduce institutional source code or internal materials.

The project name is used for professional identification and contextual description.

All institutional intellectual property and applicable confidentiality obligations remain respected.

---

## 24. Academic and Professional Background

**Eduardo Fernandes Bueno**

M.Sc. Candidate in Computer Science — State University of Londrina (UEL).

Master's Scholarship Holder (Computer Science) — Information Technology Office, ATI/UEL.

Academic background:

- Bachelor's degree in Data Science — UNIVESP.
- Bachelor's degree in Information Technology — UNIVESP.
- Bachelor's degree in Law — UEL.
- Postgraduate education in technology, education, and legal studies.

My interdisciplinary work connects software engineering, data science, data architecture, scientific research, and information governance.

My professional interests include opportunities in:

- Data Engineering.
- Data Architecture.
- Analytics Engineering.
- Data Platform Engineering.
- Applied Machine Learning.
- Research & Development.
- Academic Research.
- Scientific Computing.
- Data Governance.

---

## 25. Professional Links

- **Professional Portfolio:** https://eduardofernandesbueno.github.io/
- **GitHub:** https://github.com/eduardofernandesbueno
- **LinkedIn:** https://www.linkedin.com/in/eduardofernandesbueno/
- **ORCID:** https://orcid.org/0009-0000-8620-0211
- **Curriculum Lattes:** http://lattes.cnpq.br/8716619580595259
- **ATI/UEL Institutional Team:** https://sites.uel.br/ati/estrutura-e-equipe/
- **SBIE 2026 Publication:** https://doi.org/10.5753/sbie.2026.27263

---

## 26. Final Statement

**From institutional data integration to governed analytical systems.**

The UNIDATA/UEL experience demonstrates the importance of combining data engineering, architecture, software quality, governance, and applied scientific research.

The documented 2026 work involved the implementation and validation of data ingestion, layered transformations, quality controls, curated analytical structures, SQL serving, and BI integration within an institutional Data Lakehouse MVP.

It also provided practical experience in collaborative engineering, technical review, controlled changes, and evidence-based validation.

The purpose of this repository is to communicate those demonstrated capabilities accurately, transparently, and without disclosing institutional information.

**Engineering focus:** Reliable data platforms, governed analytical workflows, reproducible processing, and trustworthy data foundations.

**UNIDATA/UEL — Data Lakehouse Engineering, Architecture & Governance | 2026**

*Personal technical case study — Eduardo Fernandes Bueno, ATI/UEL, Brazil.*
