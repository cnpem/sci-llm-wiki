## sci-llm-wiki

_This is the repository for the article "Beyond Retrieval: Compounding Scientific Extelligence with Artificial Intelligence Wikis" (arXiv, 2026)._

SciLLMWiki is a framework for building persistent scientific memory with Large Language Models. Instead of treating papers, notes, and research questions as isolated chat sessions, it organises scientific context into human-readable markdown pages that preserve provenance, relationships, and accumulated reasoning over time.

The present repository acts as a structured knowledge substrate for AI-assisted research. Agents can ingest sources, link concepts, answer questions from the accumulated context, audit the knowledge graph, and generate literature syntheses, while researchers remain in control of interpretation, validation, and research direction.

## Skills

This wiki is designed around specialised agent skills: persistent operational routines that help ingest, organise, query, and maintain scientific knowledge without changing the underlying model. In this setup, skills act as human-guided procedures for turning papers and research notes into a coherent, linked memory system.

- **Ingestion** is the controlled entry point for new sources. The agent extracts the source, performs an initial reading, asks the researcher clarifying questions, and then writes interconnected paper, concept, model, and author pages with preserved provenance.
- **Query** turns the wiki into a reasoning workspace. The agent answers research questions by navigating accumulated context, synthesising cited evidence, surfacing contradictions, and identifying gaps that may become new persistent pages.
- **Lint** is the maintenance layer. It audits the repository for orphan pages, broken links, schema drift, inconsistent relationships, and stale claims as the knowledge graph evolves.
- **Review** supports literature synthesis. It builds structured narrative reviews from the ingested wiki context, connecting foundational work, current methods, disagreements, and open problems into manuscript-ready outlines or sections.

## SciAI Wiki overview:
<img width="1920" alt="SciAI wiki overview" src="https://github.com/user-attachments/assets/43d8c92a-0986-4bdb-b3dc-8b62460dac3b" />

#### SciAI Wiki minimal implementation stylized example (_this repository_):
<img width="600" alt="SciAI wiki minimal implementation example" src="https://github.com/user-attachments/assets/7eb920a2-c31a-40fd-acdf-1d5847a57340" />
