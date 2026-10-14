# Andrei Erofeev

## Senior ML / AI Engineer

[Google Scholar](https://scholar.google.com/citations?user=ZQv8aSgAAAAJ&hl=en&is_milestone=1) | andrei.erofeev.ds@gmail.com


## Summary

Senior ML / AI Engineer with 7+ years of experience designing, deploying and scaling machine-learning and
LLM systems in HR-tech, retail, market research and energy. Currently tech lead for a production data platform
and API on AWS, and drives AI-assisted and agentic engineering in the team. Experienced in teams of 2–15 people
in startups and large corporations. Skilled in LLM services and agentic workflows (Claude Code, multi-agent
pipelines, AWS Bedrock), NLP (HuggingFace, Transformers), data pipelines (Spark, Glue, Airflow, Databricks),
cloud infrastructure (AWS, Azure, GCP) and MLOps (Docker, Kubernetes, Terraform, CI/CD). Proven track record of
20%+ model-performance improvements, up to 180× faster data jobs and up to 90% less manual effort.

## Core Competencies

- AI Engineering: LLMs, RAG, agentic workflows, multi-agent systems, Claude Code (plugins, skills, hooks),
    AWS Bedrock, LLM-generated documentation, prompt and context engineering
- Data Science: Python (Numpy, Pandas, PySpark), PyTorch, Scikit-Learn, XGBoost/LightGBM, SHAP, Optuna,
    HuggingFace, Statistics, A/B Testing
- Data & Backend: Spark, AWS Glue, Airflow, Kafka, Databricks, PostgreSQL / Aurora, DynamoDB, FastAPI, SQL
- MLOps & Cloud: AWS (Lambda, ECS, S3, SageMaker), Azure, Google Cloud / VertexAI, Docker, Kubernetes, Terraform,
    MLFlow, KubeFlow, ArgoCD, CI/CD, Datadog
- Visualization & BI: Tableau, Power BI, Matplotlib, Plotly, Seaborn
- Soft Skills: Technical leadership, Agile/Scrum, cross-functional collaboration, mentoring, stakeholder management

## Professional Experience

#### Senior ML / AI Engineer (Tech Lead) Mar 2026 – Present
Major European HR-tech company, Germany

- Led end-to-end delivery of a new listing-performance data platform and external API, from discovery to
    production in about two months, meeting a hard deadline. It replaces a legacy system and enables new
    product features, with an estimated business impact in the low millions of euros per year.
- Designed the architecture (Kafka → S3 → AWS Glue (PySpark) orchestrated by Airflow → Aurora PostgreSQL
    Serverless → FastAPI on ECS, infrastructure in Terraform) and split the epic into the team's implementation
    stories.
- Wrote most of the API: shipped the API contract with mocked responses early so the consuming team
    could integrate in parallel; then added API-key auth and real data, with ~98.7% test coverage.
- Validated the new system against the legacy API before launch: 98.2% exact match on key conversion metrics
    over 20k+ listing-day values.
- Redesigned the historical backfill as one multi-date Glue run: two months of history went from ~65 hours to
    ~22 minutes (~180× faster) for under $1.
- Owned production readiness and incident response across Glue, Aurora, ECS and CI, including root-cause
    analysis of the first production failure.
- Introduced AI-assisted engineering in the team:
    - LLM-generated documentation that refreshes automatically after each merge (pilot).
    - A Claude Code release plugin with safety checks against force-pushes and unauthorized merges, used for
      the services' releases.
    - A multi-agent build (architect, implementer, tester, adversarial reviewers) that delivered a feature at
      98.8% test coverage.
    - Presented the AI-first agent workspace in a leadership demo.
- Earlier: built LLM and ML data services on AWS — a job-ad parser on AWS Bedrock and Lambda (taken to
    production), a scoring stack with Lambda pipelines, a DynamoDB-backed scoring API and a SageMaker vectorizer;
    S3-based replay for failed messages; an audit of monitoring alerts.

#### Senior Data Scientist Feb 2025 – Feb 2026
International retailer, Germany

- Designed and deployed labour optimization models using Python, PySpark and scikit-learn, targeting €5M in
    cost savings across the store network.
- Built end-to-end data pipelines in Azure Data Factory and Databricks to automate model training and inference,
    reducing manual effort by 90%.
- Created interactive Tableau dashboards for C-level stakeholders, enabling data-driven workforce allocation
    decisions and improving planning accuracy.

#### Machine Learning Engineer Jul 2022 – Feb 2025
Global market research company, Germany

- Developed and managed ETL pipelines for data ingestion from BigQuery and cloud storage, reducing data
    processing time by 30%.
- Led deployment of NLP services for automated survey text classification and sentiment analysis, leveraging
    PyTorch + transformers.
- Transitioned project code from PoC to production-ready, increasing test coverage to 86%.
- Led deployment processes, creating Docker containers, CI/CD, and Argo pipelines for Kubernetes.
- Enhanced forecasting models' performance by 17% through Python-based optimization.
- Refined backtesting processes for deep learning models, improving accuracy by 14% and runtime by 50%.
- Collaborated with software engineers, MLOps, and product teams to ensure efficient product delivery.

#### Machine Learning Specialist Jul 2020 – Jun 2022
Oil & gas AI startup

- Implemented state-of-the-art ML models, boosting oil production efficiency up to 20%.
- Developed a reservoir engineer AI assistant prototype for predicting oil production outcomes with more than
    89% accuracy.
- Developed domain-specific NLP pipelines to process technical reports and extract structured insights for
    engineers.
- Constructed a high-accuracy predictive model aimed at replacing conventional laboratory core tests,
    potentially reducing costs by 3-5 times.
- Engaged in client negotiations, increasing interest in the company's AI solutions.
- Mentored interns, aiding their professional development within the startup environment.

#### Research Engineer (Data Science) Aug 2019 – May 2022
Skolkovo Institute of Science and Technology, Moscow, Russia

- Improved oil production forecasting models by 32% using advanced ML techniques.
- Processed and structured data for enhanced feature engineering and ETL operations.
- Led an industrial project to estimate well performance post-treatments, improving assessments.
- Authored three AI-focused research papers with over 200 citations.

#### Junior Software Engineer Sep 2016 – Jan 2018
MIPT Center for Engineering and Technology, Moscow, Russia

- Contributed to the development of a hydrodynamic simulator in C++, enhancing simulation accuracy by 10%.
- Gained practical insights through a two-month client site assignment.
- Recognized as "Best Emerging Talent" within the organization, highlighting exceptional contributions.

## Open-Source AI Engineering

#### Claude Code plugins — [andrew-marketplace](https://github.com/AndreiErofeev/andrew-marketplace) 2026 – Present

- Build and publish plugins that extend Claude Code (the agentic coding CLI): UI panes, slash commands,
    hooks and skills, written in TypeScript with tests.
- learn_german: a side pane that shows German flashcards while the agent works on long tasks. Spaced
    repetition (Leitner), flip and typing modes, ~2,900 words (Goethe A1–B1), automatic open/close driven by
    agent activity.
- Develop the plugins with an agent-first workflow: specs, implementation, tests and docs done with Claude Code.

## Education

M.S. in Petroleum Engineering (Data Science subtrack) Sep 2017 – Jul 2019
Skolkovo Institute of Science and Technology, Moscow, Russia

M.S. in Applied Physics and Mathematics Sep 2016 – Jul 2018
Moscow Institute of Physics and Technology (MIPT), Moscow, Russia

B.S. in Applied Physics and Mathematics Sep 2012 – Jul 2016
Moscow Institute of Physics and Technology (MIPT), Moscow, Russia
