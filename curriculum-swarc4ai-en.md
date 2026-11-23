---
title: "Curriculum for Certified Professional for Software Architecture (CPSA)® Advanced Level SWARC4AI – Software Architecture for AI Systems"
publisher: "iSAQB e. V."
language: "en"
version: "2026.1-rev0"
date: "2026-11-23"
pdf: "curriculum-swarc4ai-en.pdf"
license: "Use is subject to the conditions in the section 'License and Copyright'."
generated: "Generated from the AsciiDoc sources of the curriculum. Same content as the PDF and HTML versions."
---

# Curriculum for Certified Professional for Software Architecture (CPSA)® Advanced Level **SWARC4AI** *– Software Architecture for AI Systems*

## License and Copyright

**© (Copyright), International Software Architecture Qualification Board e. V. (iSAQB® e. V.) 2026**

The curriculum may only be used subject to the following conditions:

1. You wish to obtain the CPSA Certified Professional for Software Architecture Foundation Level® certificate or the CPSA Certified Professional for Software Architecture Advanced Level® certificate. For the purpose of obtaining the certificate, it shall be permitted to use these text documents and/or curricula by creating working copies for your own computer. If any other use of documents and/or curricula is intended, for instance for their dissemination to third parties, for advertising etc., please write to [info@isaqb.org](mailto:info@isaqb.org) to enquire whether this is permitted. A separate license agreement would then have to be entered into.
2. If you are a trainer or training provider, it shall be possible for you to use the documents and/or curricula once you have obtained a usage license. Please address any enquiries to [info@isaqb.org](mailto:info@isaqb.org). License agreements with comprehensive provisions for all aspects exist.
3. If you fall neither into category 1 nor category 2, but would like to use these documents and/or curricula nonetheless, please also contact the iSAQB e. V. by writing to [info@isaqb.org](mailto:info@isaqb.org). You will then be informed about the possibility of acquiring relevant licenses through existing license agreements, allowing you to obtain your desired usage authorizations.

> **Important Notice**
>
> **We stress that, as a matter of principle, this curriculum is protected by copyright. The International Software Architecture Qualification Board e. V. (iSAQB® e. V.) has exclusive entitlement to these copyrights.**

The abbreviation "e. V." is part of the iSAQB’s official name and stands for "eingetragener Verein" (registered association), which describes its status as a legal entity according to German law. For the purpose of simplicity, iSAQB e. V. shall hereafter be referred to as iSAQB without the use of said abbreviation.

## Learning Goals Overview

- LG 1-1: Classify artificial intelligence and machine learning, data science, deep learning, and generative AI
- LG 1-2: Identify, classify, prioritize, and evaluate AI use cases from a business perspective
- LG 1-3: Classify the strengths, limitations, and typical risks of AI
- LG 1-4: Understand and explain the differences between AI systems and traditional software and decide on the appropriate type of solution
- LG 1-5: Know roles, their responsibilities, and how they collaborate in the context of AI
- LG 1-6 [OPTIONAL]: Explain the concept of the Productivity J-Curve and its significance for the introduction of AI in organizations
- LG 2-1: Know how data protection laws affect the implementation and use of AI
- LG 2-2: Analyze the requirements of the EU AI Act and derive architecture-relevant measures for data flows, logging, technical documentation, human oversight, robustness, and deployment
- LG 2-3: Classify AI systems according to the EU AI Act risk levels
- LG 2-4: Evaluate copyright, degrees of openness, and licensing terms for AI models and AI-generated content
- LG 2-5: Evaluate strategies for compliance with regulatory requirements and determine appropriate evidence and documentation artifacts for models, datasets, and operational processes
- LG 2-6: Know security pitfalls and types of attacks on ML models and select suitable security measures against attacks on AI systems
- LG 2-7: Know and apply strategies for AI risk mitigation
- LG 2-8: Understand the fundamental issues and facets of AI safety
- LG 2-9: Translate ethical guidelines and AI governance principles into organizational, development, and architectural decisions
- LG 3-1: Understand the life cycle of a machine learning or data science project
- LG 3-2: Understand data types and requirements as well as typical ML problems and their requirements
- LG 3-3: Select and compare suitable architecture and design patterns for AI systems and justify the selection based on quality requirements
- LG 3-4: Know metrics for measuring the performance of ML models
- LG 3-5: Integrate AI components into existing systems and domain architectures using suitable integration patterns, interfaces, and decoupling mechanisms
- LG 3-6: Design user interactions for AI systems that appropriately account for uncertainty, explainability, approvals, and human-in-the-loop
- LG 3-7: Analyze and design the performance and scalability of AI systems
- LG 3-8: Understand robustness in AI systems and apply strategies to increase robustness
- LG 3-9: Classify the reliability and availability of AI systems
- LG 3-10: Specify measures for the reproducibility, auditability, and traceability of models, dataset versions, prompts, configurations, and results
- LG 3-11: Classify explainability and interpretability in AI systems
- LG 3-12: Explain fault tolerance in AI systems
- LG 3-13: Document architectural decisions for AI systems
- LG 4-1: Acquire and label data
- LG 4-2: Evaluate the sources and suitability of publicly available datasets in terms of quality, licensing, representativeness, and risks
- LG 4-3: Design data pipelines and data architectures for AI systems that support quality, traceability, scalability, governance, and reusability
- LG 4-4: Know strategies for data aggregation, cleansing, transformation, enrichment, and augmentation
- LG 4-5: Know options for storing data
- LG 4-6: Classify data products, data contracts, and responsibilities in data architectures for AI systems and use them to establish robust interfaces between the business domain, data platform, and AI components
- LG 5-1: Know (hardware) requirements for training and inference
- LG 5-2: Know the trade-offs of different model architectures with regard to quality characteristics
- LG 5-3: Adjust different quality features of an ML model
- LG 5-4: Understand the costs, power consumption, and sustainable use of AI (Green IT)
- LG 5-5: Gain an overview of MLOps for automating the life cycle of a data science project
- LG 5-6: Track model training, parameters, metrics, and results
- LG 5-7: Distinguish model evaluation, system evaluation, and assessment of business value, and select suitable evaluation approaches for AI systems
- LG 5-8: Know types of drift and possible causes and solutions for them
- LG 5-9: Gain an overview of CI/CD pipelines, model management, and deployment strategies for AI models
- LG 5-10: State the advantages and disadvantages of SaaS and self-hosting and make make-or-buy decisions based on quality requirements
- LG 5-11: Design monitoring and observability for AI systems, particularly for drift, quality degradation, costs, latency, security events, and governance-relevant evidence
- LG 5-12: Understand user feedback and methods and tools for collecting it
- LG 5-13: [OPTIONAL] Know classes of MLOps tools and platforms and essential criteria for selecting them
- LG 6-1: Gain an overview of AI integration levels
- LG 6-2: Integrate AI systems into the overall architecture of an IT landscape
- LG 6-3: Develop a fundamental understanding of generative AI and how it works
- LG 6-4: Know architecture patterns for using LLMs and evaluate their limitations, risks, and trade-offs, particularly for RAG, function calling, fine-tuning, assistance systems, and agents
- LG 6-5: Know and understand use cases for RAG (Retrieval-Augmented Generation) and selected RAG techniques
- LG 6-6: Know types of prompt engineering
- LG 6-7: Analyze and architecturally classify agentic workflows with regard to planning, tool use, reflection, state management, control mechanisms, and multi-agent collaboration
- LG 6-8: Know a selection of design patterns for generative AI systems
- LG 6-9: Select techniques for evaluating LLM applications and apply them to response quality, retrieval quality, hallucinations, safety, costs, and user value
- LG 6-10: Gain an overview of well-known LLMs and selection criteria
- LG 6-11: Understand the importance of cost management for GenAI applications
- LG 6-12: Know classes of libraries, interfaces, and tools for LLM applications as well as their application contexts and selection criteria
- LG 6-13: [OPTIONAL] Know and evaluate agentic AI architectures, key architecture components, security and governance boundaries, and typical usage patterns and limitations of agent systems
- LG 6-14: Architecturally classify and apply agent runtime systems for LLM and agent systems
- LG 7-1: Use an end-to-end case study or practical project to make, document, and justify architectural decisions for an AI system and evaluate them in terms of quality, compliance, operations, and integration.

## Introduction: General information about the iSAQB Advanced Level

### What is taught in an Advanced Level module?

The module can be attended independently of a CPSA-F certification.

- The iSAQB Advanced Level offers modular training in three areas of competence with flexible training paths. It takes into account individual inclinations and specializations.
- The certification takes the form of a term paper. The assessment and oral examination are carried out by experts appointed by the iSAQB.

### What are Advanced Level (CPSA-A) graduates qualified for?

CPSA-A graduates can:

- design medium-sized to large IT systems independently and methodically
- assume technical and content-related responsibility in IT systems of medium to high criticality
- Conceptualize, design and document measures to achieve quality requirements and support development teams in the implementation of these measures
- Manage and carry out architecture-related communication in medium to large development teams

### Requirements for CPSA-A certification

- Successful training and certification as a Certified Professional for Software Architecture, Foundation Level® (CPSA-F)
- At least three years of full-time professional experience in the IT sector; collaboration on the design and development of at least two different IT systems

  - Exceptions are allowed on application (e.g., collaboration on open source projects)
- Training and further education within the scope of iSAQB Advanced Level training courses with a minimum of 70 credit points from at least three different areas of competence
- Successful completion of the CPSA-A certification exam

  
  

![Certified Professional for Software Architecture® Advanced Level (CPSA-A)](images/00-preamble/cpsa-a-logo.png)

## Essentials

### What does the module “SWARC4AI” convey?

The module presents participants with modern software architecture concepts for AI systems as a means of designing powerful, scalable and integrable AI solutions. At the end of the module, participants will be familiar with the key principles of software architecture for AI systems and will be able to apply them to the design and implementation of machine learning and generative AI systems. With the help of the modeling techniques and architecture tools taught, they will be able to seamlessly integrate AI components into existing software systems. The course covers both machine learning systems and generative AI and teaches how these can be combined with classic software systems. Participants learn what the architecture for such hybrid systems must look like in order to ensure scalability, maintainability and extensibility.

### Curriculum Structure and Recommended Durations

| Contents | Recommended minimum duration (min) |
| --- | ---: |
| Introduction to concepts relevant to software architecture for artificial intelligence | 120 |
| Compliance, security, alignment | 120 |
| Design and development of AI systems | 320 |
| Data management and data processing for AI systems | 90 |
| Important quality features for the operation of AI systems | 160 |
| System architectures and platforms for generative AI systems | 160 |
| Case studies and practical projects | 110 |
| Total | 1080 |

### Duration, didactics and further details

The duration of a training course on the SWARC4AI module should be at least 3 days, but can be longer. Providers may differ in terms of duration, didactics, type and structure of the exercises and the detailed course structure. In particular, syllabus leaves the type of examples and exercises completely open. Licensed training courses on SWARC4AI contribute to admission to the final Advanced Level certification examination (following credit points):

|  |  |
| --- | --- |
| Methodical Competence: | 10 Points |
| Technical Competence: | 20 Points |
| Communicative Competence: | 0 Points |

### Prerequisites

Participants should have the following knowledge and/or experience:

- A basic understanding of artificial intelligence, machine learning and data science
- A basic understanding of software architecture, DevOps and the design of software systems and APIs
- A basic knowledge of the Python programming language and its use for AI problems
- Overview of common libraries such as scikit-learn, TensorFlow and PyTorch

Knowledge in the following areas can be helpful for understanding some concepts

- Experience with the command line interface on Linux systems
- Knowledge from the iSAQB CPSA Foundation level training for a general understanding of software architecture, design patterns and methodologies

### Structure of the curriculum

The individual sections of the curriculum are described according to the following structure:

- **Terms/concepts**: Essential core terms of this topic.
- **Teaching/practice time**: Defines the minimum amount of teaching and practice time that must be spent on this topic or its practice in an accredited training course.
- **Learning goals**: Describes the content to be conveyed including its core terms and principles.

This section therefore also outlines the skills to be acquired in corresponding training courses.

### Supplementary Information, Terms, Translations

To the extent necessary for understanding the curriculum, we have added definitions of technical terms to the [iSAQB glossary](https://github.com/isaqb-org/glossary) and complemented them by adding referenes to the literature.

## 1. Introduction to software architecture-relevant concepts for artificial intelligence

|  |  |
| --- | --- |
| Duration: 120 min | Practice time: 0 min |

### 1.1. Terms and Concepts

AI, Generative AI, Machine Learning, Symbolic AI, Evolutionary Algorithms, Statistical Learning, Deep Learning, LLMs, Hallucination, Bias, Jagged Technological Frontier, Data Preparation, Model Training, Model Evaluation, Feature Engineering, Data Science, Data Engineering

### 1.2. Learning Goals

#### LG 1-1: Classify artificial intelligence and machine learning, data science, deep learning, and generative AI

Participants can explain the concepts of Artificial Intelligence, Machine Learning, Data Science, Deep Learning, and Generative AI, distinguish between them, and describe how they relate to one another.

#### LG 1-2: Identify, classify, prioritize, and evaluate AI use cases from a business perspective

Participants can identify and describe typical AI use cases from a business perspective. They can evaluate their suitability based on business goals, data availability and quality, technical feasibility, expected benefits, risks, integration effort, and impact on the software architecture, and can establish a well-founded prioritization.

Typical use cases include image recognition and image generation, natural language processing, predictive models, personalization, anomaly detection, chatbots, recommender systems, and intelligent assistance systems.

#### LG 1-3: Classify the strengths, limitations, and typical risks of AI

Participants can classify the strengths and limitations of AI technologies in different application contexts and explain why the suitability of AI depends heavily on the task at hand.

They can identify typical technical and societal risks, such as

- hallucinations,
- bias,
- unfairness,
- deepfakes,
- AI-assisted cyberattacks,
- safety risks in critical systems,
- social manipulation,
- infringements of intellectual property rights.

Participants are familiar with the “Jagged Technological Frontier” in relation to the task-specific suitability of AI.

#### LG 1-4: Understand and explain the differences between AI systems and traditional software and decide on the appropriate type of solution

Participants understand the differences between AI systems and traditional software:

- Data-driven (for ML) – data-centric rather than code-centric development
- Probabilistic results (non-deterministic behavior)
- Statistical validation
- Experimental design: support for rapid iteration and model testing
- Model complexity and interpretability: ML models, particularly deep learning models, can be extremely complex. Their “black-box” nature makes interpretation and explanation more difficult.
- Debugging and testing are more complex due to non-determinism.
- Model decay: continuous monitoring and retraining are necessary to maintain model performance.
- AI-specific regulations at industry and EU level must be taken into account.
- Interoperability: seamless integration into existing systems and technology stacks.

Participants can decide and explain whether and why a problem should be solved using AI or traditional software development.

#### LG 1-5: Know roles, their responsibilities, and how they collaborate in the context of AI

Participants know typical roles and their responsibilities in these contexts. In particular, these roles include:

Data Scientist, Data Analyst, Data Engineer, Machine Learning Engineer, MLOps Engineer, AI Architect, Data Architect, Business Intelligence (BI) Developer, Data Governance Specialist, and ML Researcher.

Participants also know how these roles can collaborate within a team (team topologies for ML teams).

#### LG 1-6 [OPTIONAL]: Explain the concept of the Productivity J-Curve and its significance for the introduction of AI in organizations

This phenomenon helps explain why organizations may initially experience a decline in productivity when implementing AI, followed by productivity gains as implementation progresses.

### 1.3. References

[Agrawal et al.], [Bahree 2024], [Brynjolfsson et al.], [Burkov 2019], [Chong et al.], [Dell’Acqua 2026], [Géron 2022], [Gharbi et al. 2026], [Hall et al. 2023], [Harvard et al. 2024], [Huyen 2022], [Kelleher 2015], [Roser 2022], [Tan et al.], [Vaughan 2020], [Visengeriyeva, JTF], [Wang et al. 2024]

## 2. Compliance, security, alignment

|  |  |
| --- | --- |
| Duration: 120 min | Practice time: 30 min |

### 2.1. Terms and Concepts

EU AI Act, data protection, copyright, license, open (source), AI security, jailbreak, adversarial attack, data poisoning, model inversion & extraction, AI safety, AI ethics, AI alignment, model and data documentation, transparency obligation, human oversight, data governance, AI governance, AI systems by risk levels (unacceptable risk, high risk, limited risk, minimal risk)

### 2.2. Learning Goals

#### LG 2-1: Know how data protection laws affect the implementation and use of AI

Participants are familiar with data protection laws such as the GDPR and know how they affect the collection, processing, and storage of data by AI systems.

#### LG 2-2: Analyze the requirements of the EU AI Act and derive architecture-relevant measures for data flows, logging, technical documentation, human oversight, robustness, and deployment

Participants can explain the objectives and provisions of the EU AI Act and analyze their impact on the development and use of AI systems. Furthermore, they can analyze the requirements of the EU AI Act (Trustworthy AI) regarding their impact on the development process and the architecture of the software system and derive architecture-relevant measures. In particular, they can analyze the impact on some of the following aspects and derive corresponding measures:

- Risk management system (risk mitigation)
- Data quality and data governance (quality management system)
- Creation and maintenance of comprehensive technical documentation for the AI system
- Automatic recording/logging of events in the AI system
- Provision of clear and comprehensible information to users
- Implementation of human oversight measures
- Assurance of an appropriate level of accuracy and robustness
- Implementation of cybersecurity measures

#### LG 2-3: Classify AI systems according to the EU AI Act risk levels

Participants can classify AI systems according to the EU AI Act risk levels (unacceptable risk, high risk, limited risk, minimal risk) based on concrete use cases and determine the applicable regulatory requirements.

#### LG 2-4: Evaluate copyright, degrees of openness, and licensing terms for AI models and AI-generated content

Participants can classify copyright issues relating to training data and AI-generated content and explain their impact on the development, provision, and use of AI systems.

They can distinguish different degrees of openness of ML models, for example with regard to training data, source code, model architecture, and model parameters, and evaluate licensing terms and the resulting restrictions on an AI system.

#### LG 2-5: Evaluate strategies for compliance with regulatory requirements and determine appropriate evidence and documentation artifacts for models, datasets, and operational processes

Participants understand the fundamental provisions of the EU AI Act, particularly its transparency obligations, and know strategies for complying with them as well as potential challenges.

In particular, they can select documentation artifacts for models, datasets, prompts, evaluation procedures, changes, and operational processes, and explain how these support traceability, transparency, and auditability.

Participants can classify regulatory sandboxes as an instrument for the controlled testing of innovative AI systems and explain their opportunities, limitations, and the consequences of non-compliance with the EU AI Act.

#### LG 2-6: Know security pitfalls and types of attacks on ML models and select suitable security measures against attacks on AI systems

Participants know potential security pitfalls and typical types of attacks on ML models. These include, for example:

- LLM jailbreaks through prompt engineering
- Adversarial attacks
- Data poisoning
- Model inversion and extraction

Participants can evaluate the security risks associated with these attack types for AI systems, select appropriate security measures to protect against attacks (AI Security), and justify their selection. In particular, they can evaluate options for integrating security standards and protection mechanisms into the architecture, interfaces, and operating model in terms of their suitability and select appropriate measures.

#### LG 2-7: Know and apply strategies for AI risk mitigation

Participants can explain how AI risk mitigation strategies are developed and apply them to specific AI systems. In particular, they can use the following strategies as appropriate for the situation:

- Strengthening robustness through extensive testing
- Fault-tolerant AI systems
- Transparent development
- Explainable AI (XAI)

#### LG 2-8: Understand the fundamental issues and facets of AI safety

Participants understand the fundamental issues of AI safety and are familiar with its various facets. In particular, they know specific problems such as “AI model risks by poisoning” and bias.

Participants know how bias in data and models can be detected and reduced to ensure fairness and equal treatment in AI applications.

#### LG 2-9: Translate ethical guidelines and AI governance principles into organizational, development, and architectural decisions

Participants can identify ethical issues that may arise when using AI systems and apply appropriate approaches to addressing these issues in specific use cases, for example when developing AI guidelines. To this end, participants can draw on important ethical guidelines such as the "EU Ethics Guidelines for Trustworthy AI" and translate their principles into concrete organizational, development, and architectural decisions.

Optionally, participants can apply important documents and frameworks on AI Governance to translate the core principles of AI Governance and Responsible AI into concrete guidelines for the organization, e.g.:

- OECD AI Principles, [https://oecd.ai/en/ai-principles](https://oecd.ai/en/ai-principles)
- The Asilomar AI Principles, [https://futureoflife.org/open-letter/ai-principles/](https://futureoflife.org/open-letter/ai-principles/)
- The IEEE Ethically Aligned Design framework, [https://standards.ieee.org/wp-content/uploads/import/documents/other/ead_v2.pdf](https://standards.ieee.org/wp-content/uploads/import/documents/other/ead_v2.pdf)

### 2.3. References

[ATLAS], [Bhajaria 2022], [Chen et al. 2022], [CSIRO et al. 2023], [EU AI Act], [Gharbi et al. 2026], [Hall et al. 2023], [Hotz, Best Practices], [Jarmul 2023], [Masood et al. 2023], [Molnar 2024], [Nist], [Pruksachatkun et al. 2023], [Visengeriyeva, Ethics]

## 3. Design and development of AI systems

|  |  |
| --- | --- |
| Duration: 320 min | Practice time: 45 min |

### 3.1. Terms and Concepts

CI/CD, MLOps, CRISP-ML(Q), AI application, AI engineering, ML model development, ML infrastructure, performance, robustness, reliability, fault tolerance, model-as-service, model-as-dependency, precompute, model-on-demand, hybrid serving, multi-agent system (MAS)

### 3.2. Learning Goals

#### LG 3-1: Understand the life cycle of a machine learning or data science project

Participants have an understanding of the life cycle of a machine learning or data science project. In particular, they are familiar with the following phases:

- Exploratory data analysis
- Data cleansing and preparation
- Feature engineering
- Model training and selection
- POC
- Deployment
- Maintenance

Participants know typical process models for the software development of AI systems. These include, for example:

- CRISP-ML(Q)
- Team Data Science Process
- GenAI Life Cycle

#### LG 3-2: Understand data types and requirements as well as typical ML problems and their requirements

Participants know different types of data as well as typical ML problems and use cases involving data from the following areas:

- Supervised learning
- Unsupervised learning
- Reinforcement learning

They understand the requirements these may have, for example:

- Availability of correct labels of different types
- Data volume and diversity
- Temporal or semantic dependencies in data features
- Encoding the input data of ML models, for example:

  - One-hot encodings
  - Label encodings
  - Embeddings

In particular, participants have a good understanding of the need for validation and of the typical division of data into training, validation, and test datasets.

#### LG 3-3: Select and compare suitable architecture and design patterns for AI systems and justify the selection based on quality requirements

Participants can select suitable design patterns for AI systems based on quality requirements, weigh them against each other, and justify their selection. This applies to the following design patterns:

- ML systems topology patterns
- Pipeline architecture patterns
- Model training patterns
- Model serving patterns
- Model deployment patterns

In particular, participants know transfer learning and fine-tuning as ways to adapt pretrained foundation models to existing use cases.

#### LG 3-4: Know metrics for measuring the performance of ML models

Participants are familiar with various metrics for measuring the performance of ML models, such as:

- Precision, recall
- F1 score
- Accuracy

and know how to define evaluation criteria for performance assessment.

#### LG 3-5: Integrate AI components into existing systems and domain architectures using suitable integration patterns, interfaces, and decoupling mechanisms

Participants understand how ML models can be integrated into existing systems and are familiar with the corresponding interfaces and integration points. They can apply appropriate integration patterns, interfaces, and decoupling mechanisms to integrate AI components into existing systems and domain architectures.

#### LG 3-6: Design user interactions for AI systems that appropriately account for uncertainty, explainability, approvals, and human-in-the-loop

Participants can design user interactions and user interfaces for AI systems to enable effective interactions with the ML system and optimize the user experience. In doing so, they can develop concepts that appropriately account for uncertainty, explainability, approvals, and human-in-the-loop.

#### LG 3-7: Analyze and design the performance and scalability of AI systems

Participants understand the importance of performance metrics such as latency, throughput, and resource utilization in AI systems for both training and inference, and understand how these can be optimized.

They can analyze the causes of performance and scalability issues and select appropriate measures to enable AI systems to handle increasing data volumes, user numbers, and request volumes. Based on this, they can design concepts for performance optimization and scalability of AI systems.

#### LG 3-8: Understand robustness in AI systems and apply strategies to increase robustness

Participants have an understanding of what robustness means in AI systems and can apply strategies to increase robustness in different application contexts.

#### LG 3-9: Classify the reliability and availability of AI systems

Participants understand the concepts of reliability and availability and know how to build AI systems that are stable and constantly available.

#### LG 3-10: Specify measures for the reproducibility, auditability, and traceability of models, dataset versions, prompts, configurations, and results

Participants understand the importance of reproducible and verifiable AI results and are familiar with methods for ensuring these properties. They can evaluate, select, and determine appropriate measures to ensure the reproducibility, auditability, and traceability of models, data versions, prompts, configurations, and results based on specific requirements.

#### LG 3-11: Classify explainability and interpretability in AI systems

Participants understand the importance of explainability and interpretability in AI systems and know how to ensure this in order to promote trust and transparency.

#### LG 3-12: Explain fault tolerance in AI systems

Participants are familiar with the concepts of fault tolerance and can explain how AI systems remain functional despite errors or malfunctions.

#### LG 3-13: Document architectural decisions for AI systems

Participants know how to document and justify architectural decisions for AI systems, for example using Architecture Decision Records. This includes in particular decisions and trade-offs between:

- RAG versus Fine-Tuning
- SaaS versus Self-Hosting
- Batch versus Real-Time
- Centralized versus Domain-Specific AI Services.

### 3.3. References

[Bornstein et al.], [Cdteliot], [Crowe et al. 2024], [Gharbi et al. 2026], [Heiland et al. 2023], [Hotz, Life Cycle], [Hotz, TDSP], [Koc], [Lakshmanan et al.], [ML software architecture], [Nahar et al.], [Saltz], [Savarese], [Serban], [Studer et al.], [tdcox], [TU Berlin], [Visengeriyeva, AI Agents], [Zaharia et al.]

## 4. Data management and data processing for AI systems

|  |  |
| --- | --- |
| Duration: 90 min | Practice time: 0 min |

### 4.1. Terms and Concepts

Data acquisition, labeling, data pipeline, ETL processes, data aggregation, data cleansing, transformation, augmentation, files, RDBMS, NoSQL, document databases, data products, data contracts, data architectures: Data Warehouse, Data Lake, Data Mesh

### 4.2. Learning Goals

#### LG 4-1: Acquire and label data

Participants have an overview of various methods for acquiring and labeling data and can apply appropriate data acquisition and labeling methods to specific use cases.

Participants are familiar with relevant data labeling tools such as CVAT, Label Studio, or Amazon Mechanical Turk.

#### LG 4-2: Evaluate the sources and suitability of publicly available datasets in terms of quality, licensing, representativeness, and risks

Participants can name common platforms for publicly accessible data and evaluate the suitability of the datasets available on these platforms for specific use cases based on criteria such as quality, licensing conditions, representativeness, and risks, and justify their evaluation.

#### LG 4-3: Design data pipelines and data architectures for AI systems that support quality, traceability, scalability, governance, and reusability

articipants understand the design of efficient data pipelines and architectures, data quality considerations, and storage solutions and their management. Based on this understanding, they can design data pipelines and data architectures for AI systems that address requirements for quality, traceability, scalability, governance, and reusability. In this context, participants are familiar with:

- Architectural patterns for data engineering pipelines and ETL processes
- How effective data management ensures data quality and security in AI applications

Participants have an overview of relevant tools for data engineering pipelines, such as Apache Spark and Flink.

#### LG 4-4: Know strategies for data aggregation, cleansing, transformation, enrichment, and augmentation

Participants know strategies for data aggregation, cleansing, transformation, enrichment, and augmentation.

#### LG 4-5: Know options for storing data

Participants know various options for storing data as well as their advantages and disadvantages. The options include the following technologies:

- CSV files
- Column-oriented files
- Relational and document databases
- Data warehouses
- Data lakes
- Vector databases
- Graph databases

#### LG 4-6: Classify data products, data contracts, and responsibilities in data architectures for AI systems and use them to establish robust interfaces between the business domain, data platform, and AI components

Participants are familiar with the fundamental concepts of modern data architectures for AI systems and understand the role of data products, data contracts, and business and technical responsibilities in ensuring stable and scalable data flows. They can apply these concepts to specific use cases and use data products, data contracts, and the assignment of responsibilities to design robust interfaces between business domains, data platforms, and AI components.

### 4.3. References

[Bhajaria 2022], [Bornstein et al.], [Dehghani], [Ford et al.], [Gharbi et al. 2026], [Jones], [Reis et al.], [Sanderson et al.], [Sarkis], [Serra]

## 5. Important quality features for the operation of AI systems

|  |  |
| --- | --- |
| Duration: 160 min | Practice time: 30 min |

### 5.1. Terms and Concepts

Quality features, scalability, performance optimization, monitoring, logging, feedback, FinOps for AI platforms

### 5.2. Learning Goals

#### LG 5-1: Know (hardware) requirements for training and inference

Participants know the different (hardware) requirements for training and inference, for example for TPUs, NPUs, LPUs, GPUs, or CPUs.

#### LG 5-2: Know the trade-offs of different model architectures with regard to quality characteristics

Participants can give examples of trade-offs between different model architectures with regard to quality characteristics. Particularly for scaling, efficiency, and memory footprint, participants should know the trade-offs as well as the advantages and disadvantages of important architectures such as RNNs and transformers.

#### LG 5-3: Adjust different quality features of an ML model

Participants are familiar with approaches for balancing and trading off different quality attributes of an ML model, such as accuracy, efficiency, and memory usage. They can apply appropriate techniques to balance these quality attributes based on specific requirements and trade-offs. In particular, participants can use the following techniques as appropriate for the situation:

- Quantization
- Pruning
- Distillation
- LoRA

#### LG 5-4: Understand the costs, power consumption, and sustainable use of AI (Green IT)

Participants gain an understanding of the costs, power consumption, and sustainable use of AI (Green IT). In particular, they know how to develop AI models and systems that operate efficiently by making economical use of memory, compute capacity, and storage space.

#### LG 5-5: Gain an overview of MLOps for automating the life cycle of a data science project

Participants know the term MLOps for automating the life cycle of a data science project and its relationship to DevOps.

Using a practical example, participants understand what an MLOps pipeline can look like and what insights it provides into parameters, metrics, and other aspects.

#### LG 5-6: Track model training, parameters, metrics, and results

Participants understand the tracking of model training, parameters, metrics, and results. They can apply appropriate tracking methods to systematically record and monitor training runs, parameters, metrics, and results.

#### LG 5-7: Distinguish model evaluation, system evaluation, and assessment of business value, and select suitable evaluation approaches for AI systems

Participants have an overview of approaches for evaluating ML models and AI systems built upon them. They can distinguish between model evaluation, system evaluation, and business value assessment, evaluate and select appropriate evaluation approaches for specific AI systems based on relevant requirements and quality criteria, and justify their selection.

#### LG 5-8: Know types of drift and possible causes and solutions for them

Participants are familiar with different types of drift, such as data drift or model drift, as well as possible causes and solutions.

#### LG 5-9: Gain an overview of CI/CD pipelines, model management, and deployment strategies for AI models

Participants understand CI/CD pipelines, model management, and deployment strategies for AI models.

Participants know a selection of different deployment options for AI models:

- API deployment
- Embedded deployment
- Batch prediction
- Streaming
- Containerization
- Serverless deployment
- Cloud services

Participants know common platforms and tools for model provision and for creating POCs and understand how they work conceptually.

#### LG 5-10: State the advantages and disadvantages of SaaS and self-hosting and make make-or-buy decisions based on quality requirements

Participants know the advantages and disadvantages of SaaS and self-hosting and can weigh them against each other.

Participants can make make-or-buy decisions for MLOps and AI platform systems or components based on quality requirements, cost, risk, compliance, and integration effort.

Participants have an overview of well-known SaaS AI solutions, such as Azure OpenAI Services.

#### LG 5-11: Design monitoring and observability for AI systems, particularly for drift, quality degradation, costs, latency, security events, and governance-relevant evidence

Participants understand the need for monitoring, including AI-specific requirements such as drift tracking. Based on this understanding, they can design monitoring and observability concepts for AI systems that specifically address drift, quality degradation, costs, latency, security events, and governance-related evidence.

Participants are familiar with relevant metrics such as accuracy, precision, recall, F1-score, MAE, MSE, perplexity, latency, throughput, and resource utilization, and understand why these are relevant for monitoring.

Participants are familiar with examples of monitoring tools. These include general-purpose tools such as Prometheus & Grafana, as well as ML-specific tools such as MLflow.

#### LG 5-12: Understand user feedback and methods and tools for collecting it

Participants understand the benefits of user feedback for further model training. They also know various methods and tools for collecting user feedback, such as choosing between multiple answers or flagging in Gradio.

Participants know further methods for obtaining user feedback, such as RLHF, RLAIF, and DPO.

#### LG 5-13: [OPTIONAL] Know classes of MLOps tools and platforms and essential criteria for selecting them

Participants know well-known MLOps tools and end-to-end platforms, such as:

- Domino Data Lab, h2o.ai, DVC, activeloop, aporia, argo, arize, bentoML, comet ML, DagsHub, Databricks MLOps Stacks, Feast, Kedro, Metaflow, MLflow, MLRun, prefect, PrimeHub, Weights & Biases, WhyLabs, zenML, KNIME, RapidMiner, NVIDIA AI Enterprise, watsonx.ai
- Open source: MLflow, Kubeflow, ClearML
- PaaS: AWS SageMaker, Azure ML, Google Vertex AI

### 5.3. References

[Chen et al. 2022], [Gharbi et al. 2026], [Haviv et al. 2023], [Kumara et al.], [Osipov 2022], [Salama et al.], [Tan Wei Hao et al. 2024], [Treveil et al. 2020], [Wilson 2022]

## 6. System architectures and platforms for generative AI systems

|  |  |
| --- | --- |
| Duration: 160 min | Practice time: 30 min |

### 6.1. Terms and Concepts

Generative AI, LLMs, MLflow, Managed MLflow, Azure Machine Learning, Metaflow, Generative AI, LLM, (Stable) Diffusion, Vector DB, Embedding, RNN, Transformer, RAG, Agentic Workflows etc.

### 6.2. Learning Goals

#### LG 6-1: Gain an overview of AI integration levels

Participants can distinguish between different levels of AI integration and explain their respective functions and areas of application. These include the following levels:

- Applications (e.g. coding assistants)
- AI Engineering (e.g. prompt engineering)
- ML Model Development (e.g. PyTorch)
- ML Infrastructure (e.g. vector databases).

Participants are familiar with some examples of commonly used libraries, interfaces, and tools for integrating AI models.

#### LG 6-2: Integrate AI systems into the overall architecture of an IT landscape

Participants are familiar with approaches for integrating AI systems into IT landscapes at a strategic level. For example, they can use strategic design from DDD (particularly Context Maps) to determine and document the type and degree of integration of AI systems.

Participants practice applying suitable AI integration approaches to an existing software landscape using a case study with a fictional business domain and discuss their implementation.

#### LG 6-3: Develop a fundamental understanding of generative AI and how it works

Participants have a basic understanding of generative AI, such as LLMs and diffusion models.

Participants understand how LLMs work and can classify the associated terminology: token, embedding, RNN, transformer, attention.

#### LG 6-4: Know architecture patterns for using LLMs and evaluate their limitations, risks, and trade-offs, particularly for RAG, function calling, fine-tuning, assistance systems, and agents

Participants are familiar with common patterns for using LLMs and can evaluate their limitations, risks, and trade-offs based on specific requirements and application scenarios. This includes the following patterns:

- RAG and retrieval strategies
- Function calling
- Fine-tuning
- Assistants
- Agents

#### LG 6-5: Know and understand use cases for RAG (Retrieval-Augmented Generation) and selected RAG techniques

Participants can explain typical use cases for RAG, such as "Talk to your documents/database/API".

In particular, participants can explain the basic functionality of a selection of common RAG techniques and distinguish between them, for example:

- Regular RAG, GraphRAG, CAG, agentic RAG, and multi-agent RAG
- Context enrichment techniques
- Fusion retrieval
- Intelligent reranking
- Query transformations
- Adaptive retrieval
- Iterative retrieval
- Ensemble retrieval
- Knowledge graph integration

#### LG 6-6: Know types of prompt engineering

Participants know different types of prompt engineering, such as:

- Few-shot learning
- Chain-of-thought
- Role-playing

as well as general best practices for prompting.

#### LG 6-7: Analyze and architecturally classify agentic workflows with regard to planning, tool use, reflection, state management, control mechanisms, and multi-agent collaboration

Participants understand what agentic workflows are and are familiar with the concepts of reflection, tool use, planning, and multi-agent collaboration. They can analyze agentic workflows with regard to planning, tool use, reflection, state management, control mechanisms, and multi-agent collaboration, examine the relationships between these components, and assess their implications for the architecture of AI systems.

#### LG 6-8: Know a selection of design patterns for generative AI systems

Participants know which design patterns exist for generative AI systems. They know a selection of the following patterns:

- AI Query Router (Simple Router; Ranking-based Router; Learning-based Router)
- Layered Caching Strategy Leading to Fine-Tuning
- Multiplexing AI Agents
- Fine-Tuning LLMs for Multiple Tasks
- Blending Rules-Based and Generative Approaches
- Utilizing Knowledge Graphs with LLMs
- Swarm of Generative AI Agents
- Modular Monolith LLM Approach with Composability
- Memory Cognition for LLMs
- Red and Blue Team Dual-Model Evaluation

#### LG 6-9: Select techniques for evaluating LLM applications and apply them to response quality, retrieval quality, hallucinations, safety, costs, and user value

Participants are familiar with several techniques for evaluating LLM applications. They can evaluate their suitability for specific evaluation objectives, select appropriate techniques, and apply them to assess response quality, retrieval quality, hallucinations, security, costs, and user value. These may include the following techniques:

- Scoring
- Human feedback
- Comparative evaluation
- Model-based evaluation

Participants know common evaluation frameworks such as LangSmith or LangFuse for dealing with indeterminacy and errors in AI systems.

#### LG 6-10: Gain an overview of well-known LLMs and selection criteria

Participants are familiar with common LLMs such as GPT, Claude, Gemini, Llama, Mistral, or Luminous and can explain their key differences as well as relevant criteria for selecting a suitable LLM.

#### LG 6-11: Understand the importance of cost management for GenAI applications

Participants understand the importance of cost management for GenAI applications.

#### LG 6-12: Know classes of libraries, interfaces, and tools for LLM applications as well as their application contexts and selection criteria

Participants know some examples of common libraries, interfaces, and tools related to LLM applications, such as the OpenAI API or LangChain.

#### LG 6-13: [OPTIONAL] Know and evaluate agentic AI architectures, key architecture components, security and governance boundaries, and typical usage patterns and limitations of agent systems

Participants are familiar with agentic AI software architectures, AI agent architectural components, and types of AI agent architectures. They can evaluate different agentic AI architectures in terms of their key architectural components, typical usage patterns, limitations, and security and governance requirements, and justify their assessment based on specific application scenarios.

#### LG 6-14: Architecturally classify and apply agent runtime systems for LLM and agent systems

Participants understand agent runtime systems as an architectural control and integration layer for probabilistic AI components such as LLMs and agents. They can describe harness approaches using established architecture concepts such as encapsulation, interface control, invariants, operational boundaries, observability, policy enforcement, fault isolation, controlled change, governance, and auditability, and can apply these approaches when designing production-ready AI systems.

In particular, they can derive how an agent runtime system:

- limits the autonomy of an AI component through clear interfaces, permitted actions, and operational boundaries,
- controls inputs, context, tool access, state, and outputs,
- enforces system invariants and policies,
- isolates errors and unsafe model outputs,
- ensures observability, traceability, and auditability,
- enables controlled changes to prompts, models, retrieval components, and tools,
- supports the secure operation and safe evolution of AI systems.

### 6.3. References

[Bahree 2024], [bornstein-radovanic], [Dibia 2025], [Foster 2023], [Gharbi et al. 2026], [Gradient Flow], [Koc], [Parnin], [Spirin et al.]

## 7. Case studies and practical projects

|  |  |
| --- | --- |
| Duration: 110 min | Practice time: 110 min |

### 7.1. Learning Goals

#### LG 7-1: Use an end-to-end case study or practical project to make, document, and justify architectural decisions for an AI system and evaluate them in terms of quality, compliance, operations, and integration.

Participants can independently make, document, and justify architectural decisions for an AI system based on an end-to-end case study or practical project. They can evaluate these decisions with regard to relevant quality requirements, regulatory requirements (compliance), operational aspects, and integration into existing IT systems.

### 7.2. References

[Gharbi et al. 2026]

## References

This section contains references that are cited in the curriculum.

**A**

- [Agrawal et al.] A. Agrawal, J. Gans, A. Goldfarb:  Prediction Machines: The Simple Economics of Artificial Intelligence [https://www.predictionmachines.ai/](https://www.predictionmachines.ai/)
- [ATLAS] ATLAS - Adversarial Threat Landscape for Artificial-Intelligence Systems. [https://github.com/mitre/advmlthreatmatrix](https://github.com/mitre/advmlthreatmatrix)

**B**

- [Bahree 2024] Bahree, A.: Generative AI in Action [https://www.manning.com/books/generative-ai-in-action](https://www.manning.com/books/generative-ai-in-action)
- [Bhajaria 2022] N. Bhajaria: Data Privacy - A runbook for engineers [https://www.manning.com/books/data-privacy](https://www.manning.com/books/data-privacy)
- [Bornstein et al.] M. Bornstein, J. Li, M. Casado: Emerging Architectures for Modern Data Infrastructure [https://a16z.com/emerging-architectures-for-modern-data-infrastructure/](https://a16z.com/emerging-architectures-for-modern-data-infrastructure/)
- [bornstein-radovanic] M. Bornstein and R. Radovanovic: Emerging Architectures for LLM Applications [https://a16z.com/emerging-architectures-for-llm-applications/](https://a16z.com/emerging-architectures-for-llm-applications/)
- [Brynjolfsson et al.] Brynjolfsson, E.: The Productivity J-Curve: How Intangibles complement General Purpose Technologies [https://www.nber.org/system/files/working_papers/w25148/w25148.pdf](https://www.nber.org/system/files/working_papers/w25148/w25148.pdf)
- [Burkov 2019] Burkov, A.: The Hundred-Page Machine Learning Book [https://themlbook.com/](https://themlbook.com/)

**C**

- [Cdteliot] AI Agents: Understanding Their Impact and Functions [https://www.perplexity.ai/page/ai-agents-understanding-their-bL1Mg8FeStyUB4o9u3HT5Q](https://www.perplexity.ai/page/ai-agents-understanding-their-bL1Mg8FeStyUB4o9u3HT5Q)
- [Chen et al. 2022] C. Chen, N. R. Murphy, K. Parisa, D. Sculley, T. Underwood: Reliable Machine Learning [https://www.oreilly.com/library/view/reliable-machine-learning/9781098106218/](https://www.oreilly.com/library/view/reliable-machine-learning/9781098106218/)
- [Chong et al.] J. Chong, Y. C. Chang: How to Lead in Data Science [https://www.manning.com/books/how-to-lead-in-data-science](https://www.manning.com/books/how-to-lead-in-data-science)
- [Crowe et al. 2024] R. Crowe, H. Hapke, E. Caveness, D. Zhu: Machine Learning Production Systems [https://learning.oreilly.com/library/view/machine-learning-production/9781098156008/](https://learning.oreilly.com/library/view/machine-learning-production/9781098156008/)
- [CSIRO et al. 2023] CSIRO, Q. Lu, J. Wittle, X. Xu, L. Xhu: Responsible AI: Best Practices for Creating Trustworthy AI Systems [https://www.oreilly.com/library/view/responsible-ai-best/9780138073947/](https://www.oreilly.com/library/view/responsible-ai-best/9780138073947/)

**D**

- [Dehghani] Z. Dehghani: Data Mesh [https://learning.oreilly.com/library/view/data-mesh/9781492092384/](https://learning.oreilly.com/library/view/data-mesh/9781492092384/)
- [Dell’Acqua 2026] Fabrizio Dell’Acqua et al.: Paper: "Navigating the Jagged Technological Frontier: Field Experimental Evidence of the Effects of AI on Knowledge Worker Productivity and Quality" [https://doi.org/10.1287/orsc.2025.21838](https://doi.org/10.1287/orsc.2025.21838)
- [Dibia 2025] V. Dibia with C. Wang: Multi-Agent Systems with AutoGen [https://www.manning.com/books/multi-agent-systems-with-autogen](https://www.manning.com/books/multi-agent-systems-with-autogen)

**E**

- [EU AI Act] EU AI Act [https://artificialintelligenceact.eu/de/ai-act-explorer/](https://artificialintelligenceact.eu/de/ai-act-explorer/)

**F**

- [Ford et al.] N. Ford, M. Richards, P. Sadalage, Z. Dehghani Software Architecture: The Hard Parts. [https://learning.oreilly.com/library/view/software-architecture-the/9781492086888/](https://learning.oreilly.com/library/view/software-architecture-the/9781492086888/)
- [Foster 2023] D. Foster: Generative Deep Learning, 2nd Edition [https://www.oreilly.com/library/view/generative-deep-learning/9781098134174/](https://www.oreilly.com/library/view/generative-deep-learning/9781098134174/)

**G**

- [Gharbi et al. 2026] M. Gharbi, H. Klus, H. Tiemeyer, M. Zhang: Praxiswissen Softwarearchitektur für KI-Systeme: Grundlagen, Konzepte, Techniken und Plattformen. Aus- und Weiterbildung zum Certified Professional for Software Architecture – Advanced Level – Modul SWARC4AI nach iSAQB®-Standard. dpunkt.verlag, 2026.
- [Géron 2022] Aurélien Géron: Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow [https://learning.oreilly.com/library/view/hands-on-machine-learning/9781098125967/](https://learning.oreilly.com/library/view/hands-on-machine-learning/9781098125967/)
- [Gradient Flow] LLM Routers Unpacked [https://gradientflow.com/llm-routers-unpacked/](https://gradientflow.com/llm-routers-unpacked/)

**H**

- [Hall et al. 2023] P. Hall, J. Curtis, P. Pandey: Machine Learning for High-Risk Applications [https://www.oreilly.com/library/view/machine-learning-for/9781098102425/](https://www.oreilly.com/library/view/machine-learning-for/9781098102425/)
- [Harvard et al. 2024] Harvard Business Review, E. Mollick, D. De Cremer, T. Neeley, P. Sinha: Generative AI: The Insights You Need. (Generative AI Use Cases) [https://learning.oreilly.com/library/view/generative-ai-the/9781647826406/](https://learning.oreilly.com/library/view/generative-ai-the/9781647826406/)
- [Haviv et al. 2023] Y. Haviv, N. Gift: Implementing MLOps in the Enterprise [https://www.oreilly.com/library/view/implementing-mlops-in/9781098136574/](https://www.oreilly.com/library/view/implementing-mlops-in/9781098136574/)
- [Heiland et al. 2023] L. Heiland, M. Hauser, J. Bogner: Design Patterns for AI-based Systems: A Multivocal Literature Review and Pattern Repository. 2023 IEEE/ACM 2nd International Conference on AI Engineering–Software Engineering for AI (CAIN). IEEE, 2023.
- [Hotz, Best Practices] N. Hotz: 15 Data Science Documentation Best Practices [https://www.datascience-pm.com/documentation-best-practices/](https://www.datascience-pm.com/documentation-best-practices/)
- [Hotz, Life Cycle] N. Hotz: What is a Data Science Life Cycle? [https://www.datascience-pm.com/data-science-life-cycle/](https://www.datascience-pm.com/data-science-life-cycle/)
- [Hotz, TDSP] N. Hotz: What is TDSP [https://www.datascience-pm.com/tdsp/](https://www.datascience-pm.com/tdsp/)
- [Huyen 2022] C. Huyen: Designing Machine Learning Systems [https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/)

**J**

- [Jarmul 2023] K. Jarmul: Practical Data Privacy [https://www.oreilly.com/library/view/practical-data-privacy/9781098129453/](https://www.oreilly.com/library/view/practical-data-privacy/9781098129453/)
- [Jones] A. Jones: Driving Data Quality with Data Contracts [https://learning.oreilly.com/library/view/driving-data-quality/9781837635009/](https://learning.oreilly.com/library/view/driving-data-quality/9781837635009/)

**K**

- [Kelleher 2015] John D. Kelleher, Brian Mac Namee, and Aoife D’Arcy: Fundamentals of Machine Learning for Predictive Data Analytics [https://mitpress.mit.edu/9780262029445/fundamentals-of-machine-learning-for-predictive-data-analytics](https://mitpress.mit.edu/9780262029445/fundamentals-of-machine-learning-for-predictive-data-analytics)
- [Koc] V. Koc: Generative AI Design Patterns: A Comprehensive Guide [https://towardsdatascience.com/generative-ai-design-patterns-a-comprehensive-guide-41425a40d7d0](https://towardsdatascience.com/generative-ai-design-patterns-a-comprehensive-guide-41425a40d7d0)
- [Kumara et al.] I. Kumara, R., D. Di Nucci, W. J. Van Den Heuvel, D. A. Tamburri: Requirements and Reference Architecture for MLOps:Insights from Industry [https://www.techrxiv.org/doi/full/10.36227/techrxiv.21397413.v1](https://www.techrxiv.org/doi/full/10.36227/techrxiv.21397413.v1)

**L**

- [Lakshmanan et al.] V. Lakshmanan, S Robinson, M. Munn: Machine Learning Design Patterns [https://learning.oreilly.com/library/view/machine-learning-design/9781098115777/](https://learning.oreilly.com/library/view/machine-learning-design/9781098115777/)

**M**

- [Masood et al. 2023] A. Masood, H. Dawe: Responsible AI in the Enterprise [https://www.oreilly.com/library/view/responsible-ai-in/9781803230528/](https://www.oreilly.com/library/view/responsible-ai-in/9781803230528/)
- [ML software architecture] ML software architecture [https://appliedaiinitiative.notion.site/ML-software-architecture-790b9f5fcfcf408884287acb82f4d75e](https://appliedaiinitiative.notion.site/ML-software-architecture-790b9f5fcfcf408884287acb82f4d75e)
- [Molnar 2024] C. Molnar: Interpretable Machine Learning, 2nd ed. [https://christophm.github.io/interpretable-ml-book/](https://christophm.github.io/interpretable-ml-book/)

**N**

- [Nahar et al.] N. Nahar, et al.: A meta-summary of challenges in building products with ml components–collecting experiences from 4758+ practitioners. 2023 IEEE/ACM 2nd International Conference on AI Engineering–Software Engineering for AI (CAIN). IEEE, 2023.
- [NirDiamant] RAG Techniques [https://github.com/NirDiamant/RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques)
- [Nist] NIST AI Risk Management Framework. [https://www.nist.gov/itl/ai-risk-management-framework](https://www.nist.gov/itl/ai-risk-management-framework)

**O**

- [Osipov 2022] C. Osipov: MLOps Engineering at Scale [https://www.manning.com/books/mlops-engineering-at-scale](https://www.manning.com/books/mlops-engineering-at-scale)

**P**

- [Parnin] Building Your Own Product Copilot: Challenges, Opportunities, and Needs [https://arxiv.org/pdf/2312.14231v1](https://arxiv.org/pdf/2312.14231v1)
- [Pruksachatkun et al. 2023] Y. Pruksachatkun, M. Mcateer, S. Majudmar: Practicing Trustworthy Machine Learning [https://www.oreilly.com/library/view/practicing-trustworthy-machine/9781098120269/](https://www.oreilly.com/library/view/practicing-trustworthy-machine/9781098120269/)

**R**

- [Reis et al.] J. Reis, M. Housley: Fundamentals of Data Engineering [https://learning.oreilly.com/library/view/fundamentals-of-data/9781098108298/](https://learning.oreilly.com/library/view/fundamentals-of-data/9781098108298/)
- [Roser 2022] Roser, Max: Brief History of AI: [https://ourworldindata.org/brief-history-of-ai](https://ourworldindata.org/brief-history-of-ai)

**S**

- [Salama et al.] K. Salama, J. Kazmierczak, D. Schut: Practitioners guide to MLOps: A framework for continuous delivery and automation of machine learning. [https://services.google.com/fh/files/misc/practitioners_guide_to_mlops_whitepaper.pdf](https://services.google.com/fh/files/misc/practitioners_guide_to_mlops_whitepaper.pdf)
- [Saltz] J. Saltz: The GenAI Life Cycle [https://www.datascience-pm.com/the-genai-life-cycle/](https://www.datascience-pm.com/the-genai-life-cycle/)
- [Sanderson et al.] C. Sanderson, M. Freeman: Data Contracts [https://learning.oreilly.com/library/view/data-contracts/9781098157623/](https://learning.oreilly.com/library/view/data-contracts/9781098157623/)
- [Sarkis] A. Sarkis: Training Data for Machine Learning [https://learning.oreilly.com/library/view/training-data-for/9781492094517/](https://learning.oreilly.com/library/view/training-data-for/9781492094517/)
- [Savarese] S. Savarese: How AI Agents Will Revolutionize the AI Enterprise [https://www.salesforce.com/blog/how-ai-agents-will-revolutionize-the-ai-enterprise/](https://www.salesforce.com/blog/how-ai-agents-will-revolutionize-the-ai-enterprise/)
- [Serban] A. Serban, J. Visser: "Adapting software architectures to machine learning challenges." 2022 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER). IEEE, 2022.
- [Serra] J. Serra: Deciphering Data Architectures [https://learning.oreilly.com/library/view/deciphering-data-architectures/9781098150754/](https://learning.oreilly.com/library/view/deciphering-data-architectures/9781098150754/)
- [Spirin et al.] N. Spirin, M. Balint: Mastering LLM Techniques: LLMOps [https://developer.nvidia.com/blog/mastering-llm-techniques-llmops/](https://developer.nvidia.com/blog/mastering-llm-techniques-llmops/)
- [Studer et al.] S. Studer et al.: Towards CRISP-ML(Q): A Machine Learning Process Model with Quality Assurance Methodology [https://arxiv.org/abs/2003.05155](https://arxiv.org/abs/2003.05155)

**T**

- [Tan et al.] D. Tan, A. Leung, D. Colls: Effective Machine Learning Teams [https://learning.oreilly.com/library/view/effective-machine-learning/9781098144623/](https://learning.oreilly.com/library/view/effective-machine-learning/9781098144623/)
- [Tan Wei Hao et al. 2024] B. Tan Wei Hao, S. Padmanabhan, V. Mallya: Design a Machine Learning System (From Scratch) [https://www.manning.com/books/design-a-machine-learning-system-design-from-scratch](https://www.manning.com/books/design-a-machine-learning-system-design-from-scratch)
- [tdcox] MLOps Roadmap 2024 - DRAFT [https://github.com/cdfoundation/sig-mlops/blob/main/roadmap/2024/MLOpsRoadmap2024.md](https://github.com/cdfoundation/sig-mlops/blob/main/roadmap/2024/MLOpsRoadmap2024.md)
- [Treveil et al. 2020] M. Treveil, N. Omont, C. Stenac, K. Lefevre, D. Phan, J. Zentici, A. Lavoillotte, M. Miyazaki, L. Heidmann: Introducing MLOps [https://www.oreilly.com/library/view/introducing-mlops/9781492083283/](https://www.oreilly.com/library/view/introducing-mlops/9781492083283/)
- [TU Berlin] Architecture of Machine Learning Systems (TU Berlin, SS 2024): [https://mboehm7.github.io/teaching/ss24_amls/index.htm](https://mboehm7.github.io/teaching/ss24_amls/index.htm)

**V**

- [Vaughan 2020] Vaughan, D.: Analytical Skills for AI and Data Science (AI Use Cases) [https://learning.oreilly.com/library/view/analytical-skills-for/9781492060932/](https://learning.oreilly.com/library/view/analytical-skills-for/9781492060932/)
- [Visengeriyeva, JTF] Visengeriyeva, L.: Defining Jagged Technological Frontier: [https://www.perplexity.ai/page/defining-jagged-technological-iF8sDPVFQEKSdd2oyytztA](https://www.perplexity.ai/page/defining-jagged-technological-iF8sDPVFQEKSdd2oyytztA)
- [Visengeriyeva, AI Agents] Visengeriyeva, L.: AI Agents vs. Traditional Models [https://www.perplexity.ai/page/ai-agents-vs-traditional-model-JFf4gKT0RySW_Ehvbxho2g](https://www.perplexity.ai/page/ai-agents-vs-traditional-model-JFf4gKT0RySW_Ehvbxho2g)
- [Visengeriyeva, Ethics] Model Governance, Ethics, Responsible AI (Linksammlung) [https://github.com/visenger/Awesome-ML-Model-Governance](https://github.com/visenger/Awesome-ML-Model-Governance)

**W**

- [Wang et al. 2024] C. Wang et al.: Quality Assurance for Artificial Intelligence: A Study of Industrial Concerns, Challenges and Best Practices [https://arxiv.org/pdf/2402.16391](https://arxiv.org/pdf/2402.16391)
- [Wilson 2022] B. Wilson: Machine Learning Engineering in Action [https://www.manning.com/books/machine-learning-engineering-in-action](https://www.manning.com/books/machine-learning-engineering-in-action)

**Z**

- [Zaharia et al.] M. Zaharia et al.: The Shift from Models to Compound AI Systems [https://bair.berkeley.edu/blog/2024/02/18/compound-ai-systems/](https://bair.berkeley.edu/blog/2024/02/18/compound-ai-systems/)
