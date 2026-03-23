---
layout: home
title: Home
---

I bring a strong foundation in machine learning, with extensive experience in natural language processing and knowledge graph technologies. I have designed, implemented, and deployed ML systems in collaborative, multi-stakeholder projects, turning complex concepts into reliable, data-driven solutions. My experience in teaching and mentoring has strengthened my ability to communicate technical concepts clearly and work effectively across interdisciplinary teams.

## Experience

**Research Associate** — House of Computing and Data Science, Hamburg *(August 2024–Present)*
- Leading a team in a multi-partner R&D project focused on AI support for emergency response
- Architecting scalable NLP and information extraction pipelines for operational text data
- Translating stakeholder requirements into deployable technical solutions in collaboration with external partners

**Research Associate** — University of Hamburg *(August 2021–July 2024)*
- Conducted applied research at the intersection of NLP, semantic web technologies, and knowledge graphs
- Contributed to project acquisition, technical planning, teaching and supervision of junior researchers

**Research Associate** — Fraunhofer IAIS, Dresden *(Dec 2019–July 2021)*
- Engineered and integrated a task-oriented dialogue system into an operational software environment
- Developed information extraction pipelines to structure and normalize information from heterogeneous text sources

**Intern** — Fraunhofer IPA, Stuttgart *(Oct 2017–March 2018)*
- Contributed to the development of a long-term SLAM system for mobile robotic platforms

## Education

**Ph.D.**, University of Hamburg *(Nov 2021–Feb 2026)*
Thesis: *Knowledge Graph-Guided Information Extraction*

**Diploma in Computer Science**, Technical University of Dresden *(Oct 2014–Oct 2019)*

## Technical Skills

- **Languages:** Python (7+ years), C++ (2 years), Java (2 years)
- **ML/DL:** PyTorch, large-scale model training, LLM fine-tuning & prompting, Agentic AI
- **Frameworks:** Transformers, LangGraph, vLLM, Elasticsearch, FAISS
- **Systems:** Docker, FastAPI, CI/CD pipelines, GPU cluster management
- **Data:** RAG pipelines, relational databases, knowledge graphs

## Languages

German (native) · English (fluent) · Japanese (basic)

## Selected Publications

See the full [publications list](/publications/).

{% assign sorted_pubs = site.data.publications.publications | where: "first_author", true | sort: "year" | reverse %}
{% for pub in sorted_pubs limit:5 %}
- {% if pub.doi %}[{{ pub.title }}]({{ pub.doi }}){% elsif pub.url %}[{{ pub.title }}]({{ pub.url }}){% else %}{{ pub.title }}{% endif %} — *{{ pub.venue }}*, {{ pub.year }}
{% endfor %}

## Projects

See the [projects page](/projects/) for demos and tools.

## Contact

[cedric.moeller@icloud.com](mailto:cedric.moeller@icloud.com) · [LinkedIn](https://www.linkedin.com/in/cedric-moeller-784a501a1/) · [GitHub](https://github.com/cedricmoeller)
